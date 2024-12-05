# Chapter 01 - Abstract Data Types

---

## Array and Array Operations

---

### 1. Which of these best describes an array?

a) A data structure that shows a hierarchical behavior  
b) Container of objects of similar types  
c) Arrays are immutable once initialised  
d) Array is not a data structure

**Answer:** b
**Explanation:**
Array contains elements only of the same type.

---

### 2. How do you initialize an array in C?

a) int arr[3] = (1,2,3);  
b) int arr(3) = {1,2,3};  
c) int arr[3] = {1,2,3};  
d) int arr(3) = (1,2,3);

**Answer:** c
**Explanation:**
This is the syntax to initialize an array in C.

---

### 3. How do you instantiate an array in Java?

a) int arr[] = new int(3);  
b) int arr[];  
c) int arr[] = new int[3];  
d) int arr() = new int(3);

**Answer:** c
**Explanation:**
Note that int arr[]; is declaration whereas int arr[] = new int[3]; is to instantiate an array.

---

### 4. Which of the following is the correct way to declare a multidimensional array in Java?

a) int[] arr;  
b) int arr[[]];  
c) int[][]arr;  
d) int[[]] arr;

**Answer:** c
**Explanation:**
The syntax to declare multidimensional array in java is either int[][] arr; or int arr[][];

---

### 5. What is the output of the following Java code?

```
public class array
{
	public static void main(String args[])
	{
		int []arr = {1,2,3,4,5};
		System.out.println(arr[2]);
		System.out.println(arr[4]);
	}
}
```

a) 3 and 5  
b) 5 and 3  
c) 2 and 4  
d) 4 and 2

**Answer:** a
**Explanation:**
Array indexing starts from 0.

---

### 6. What is the output of the following Java code?

```
public class array
{
	public static void main(String args[])
	{
		int []arr = {1,2,3,4,5};
		System.out.println(arr[5]);
	}
}

```

a) 4  
b) 5  
c) ArrayIndexOutOfBoundsException  
d) InavlidInputException

**Answer:** c
**Explanation:**
Trying to access an element beyond the limits of an array gives ArrayIndexOutOfBoundsException.

---

### 7. When does the ArrayIndexOutOfBoundsException occur?

a) Compile-time  
b) Run-time  
c) Not an error  
d) Not an exception at all

**Answer:** b
**Explanation:**
ArrayIndexOutOfBoundsException is a run-time exception and the compilation is error-free.

---

### 8. Which of the following concepts make extensive use of arrays?

a) Binary trees  
b) Scheduling of processes  
c) Caching  
d) Spatial locality

**Answer:**d
**Explanation:**
Whenever a particular memory location is referred to, it is likely that the locations nearby are also referred, arrays are stored as contiguous blocks in memory, so if you want to access array elements, spatial locality makes it to access quickly.

---

### 9. What are the advantages of arrays?

a) Objects of mixed data types can be stored  
b) Elements in an array cannot be sorted  
c) Index of first element of an array is 1  
d) Easier to store elements of same data type

**Answer:** d
**Explanation:**
Arrays store elements of the same data type and present in continuous memory locations.

---

### 10. What are the disadvantages of arrays?

a) Data structure like queue or stack cannot be implemented  
b) There are chances of wastage of memory space if elements inserted in an array are lesser than the allocated size  
c) Index value of an array can be negative  
d) Elements are sequentially accesse

**Answer:** b
**Explanation:**
Arrays are of fixed size. If we insert elements less than the allocated size, unoccupied positions can’t be used again. Wastage will occur in memory.

---

### 11. Assuming int is of 4bytes, what is the size of int arr[15];?

a) 15  
b) 19  
c) 11  
d) 60

**Answer:** d
**Explanation:**
Since there are 15 int elements and each int is of 4bytes, we get 15\*4 = 60bytes.

---

### 12. In general, the index of the first element in an array is \***\*\_\_\*\***

a) 0  
b) -1  
c) 2  
d) 1

**Answer:**a
**Explanation:**
In general, Array Indexing starts from 0. Thus, the index of the first element in an array is 0.

---

### 13. Elements in an array are accessed **\*\***\_**\*\***

a) randomly  
b) sequentially  
c) exponentially  
d) logarithmically

**Answer:** b
**Explanation:**
Elements in an array are accessed randomly. In Linked lists, elements are accessed sequentially.

---

## Stack Operation - 1

### 1. Process of inserting an element in stack is called \***\*\_\_\_\_\*\***

a) Create  
b) Push  
c) Evaluation  
d) Pop

**Answer:**b
**Explanation:**
Push operation allows users to insert elements in the stack. If the stack is filled completely and trying to perform push operation stack – overflow can happen.

---

### 2. Process of removing an element from stack is called \***\*\_\_\*\***

a) Create  
b) Push  
c) Evaluation  
d) Pop

**Answer:** d
**Explanation:**
Elements in the stack are removed using pop operation. Pop operation removes the top most element in the stack i.e. last entered element.

---

### 3. In a stack, if a user tries to remove an element from an empty stack it is called \***\*\_\*\***

a) Underflow  
b) Empty collection  
c) Overflow  
d) Garbage Collection

**Answer:** a
**Explanation:**
Underflow occurs when the user performs a pop operation on an empty stack. Overflow occurs when the stack is full and the user performs a push operation. Garbage Collection is used to recover the memory occupied by objects that are no longer used.

---

### 4. Pushing an element into stack already having five elements and stack size of 5, then stack becomes \***\*\_\_\_\*\***

a) Overflow  
b) Crash  
c) Underflow  
d) User flow

**Answer:** a
**Explanation:**
Underflow occurs when the user performs a pop operation on an empty stack. Overflow occurs when the stack is full and the user performs a push operation. Garbage Collection is used to recover the memory occupied by objects that are no longer used.

---

### 5. Entries in a stack are “ordered”. What is the meaning of this statement?

a) A collection of stacks is sortable  
b) Stack entries may be compared with the ‘<‘ operation  
c) The entries are stored in a linked list  
d) There is a Sequential entry that is one by one

**Answer:** d
**Explanation:**
In stack data structure, elements are added one by one using push operation. Stack follows LIFO Principle i.e. Last In First Out(LIFO).

---

### 6. Which of the following is not the application of stack?

a) A parentheses balancing program  
b) Tracking of local variables at run time  
c) Compiler Syntax Analyzer  
d) Data Transfer between two asynchronous process

**Answer:** d
**Explanation:**
Data transfer between the two asynchronous process uses the queue data structure for synchronisation. The rest are all stack applications.

---

### 7. Consider the usual algorithm for determining whether a sequence of parentheses is balanced. The maximum number of parentheses that appear on the stack AT ANY ONE TIME when the algorithm analyzes: (()(())(()))?

a) 1  
b) 2  
c) 3  
d) 4 or more

**Answer:** c
**Explanation:**
In the entire parenthesis balancing method when the incoming token is a left parenthesis it is pushed into stack. A right parenthesis makes pop operation to delete the elements in stack till we get left parenthesis as top most element. 3 elements are there in stack before right parentheses comes. Therefore, maximum number of elements in stack at run time is 3.

---

### 8. Consider the usual algorithm for determining whether a sequence of parentheses is balanced. Suppose that you run the algorithm on a sequence that contains 2 left parentheses and 3 right parentheses (in some order). The maximum number of parentheses that appear on the stack AT ANY ONE TIME during the computation?

a) 1  
b) 2  
c) 3  
d) 4 or more

**Answer:** b
**Explanation:**
In the entire parenthesis balancing method when the incoming token is a left parenthesis it is pushed into stack. A right parenthesis makes pop operation to delete the elements in stack till we get left parenthesis as top most element. 2 left parenthesis are pushed whereas one right parenthesis removes one of left parenthesis. 2 elements are there before right parenthesis which is the maximum number of elements in stack at run time.

---

### 9. What is the value of the postfix expression 6 3 2 4 + – \*?

a) 1  
b) 40  
c) 74  
d) -18

**Answer:** d
**Explanation:**
Postfix Expression is (6\*(3-(2+4))) which results -18 as output.

---

### 10. Here is an infix expression: 4 + 3*(6*3-12). Suppose that we are using the usual stack algorithm to convert the expression from infix to postfix notation. The maximum number of symbols that will appear on the stack AT ONE TIME during the conversion of this expression?

a) 1  
b) 2  
c) 3  
d) 4

**Answer:** d
**Explanation:**
When we perform the conversion from infix to postfix expression +, _, (, _ symbols are placed inside the stack. A maximum of 4 symbols are identified during the entire conversion.

---

###

**Answer:**
**Explanation:**

---

###

**Answer:**
**Explanation:**

---

###

**Answer:**
**Explanation:**

---

###

**Answer:**
**Explanation:**

---

###

**Answer:**
**Explanation:**

---

###

**Answer:**
**Explanation:**

---

###

**Answer:**
**Explanation:**

---

###

**Answer:**
**Explanation:**

---

###

**Answer:**
**Explanation:**

---

###

**Answer:**
**Explanation:**

---

###

**Answer:**
**Explanation:**

---

###

**Answer:**
**Explanation:**

---

###

**Answer:**
**Explanation:**

---

###

**Answer:**
**Explanation:**

---

###

**Answer:**
**Explanation:**

---

###

**Answer:**
**Explanation:**

---

###

**Answer:**
**Explanation:**

---

###

**Answer:**
**Explanation:**

---

###

**Answer:**
**Explanation:**

---

###

**Answer:**
**Explanation:**

---

###

**Answer:**
**Explanation:**

---

###

**Answer:**
**Explanation:**

---

###

**Answer:**
**Explanation:**

---

###

**Answer:**
**Explanation:**

---

###

**Answer:**
**Explanation:**

---

###

**Answer:**
**Explanation:**

---

###

**Answer:**
**Explanation:**

---

###

**Answer:**
**Explanation:**

---

###

**Answer:**
**Explanation:**

---

###

**Answer:**
**Explanation:**

---

###

**Answer:**
**Explanation:**

---

###

**Answer:**
**Explanation:**

---
