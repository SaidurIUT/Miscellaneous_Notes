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
