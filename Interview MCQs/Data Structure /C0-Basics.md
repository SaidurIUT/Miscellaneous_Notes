## Chapter - 0: Basics of Data Structure

---

---

### 1. What is a data structure?

a) A programming language  
b) A collection of algorithms  
c) A way to store and organize data  
d) A type of computer hardware

**Answer:** c  
**Explanation:**  
A data structure is a way to store and organize data efficiently, enhancing access and manipulation, unlike programming languages, algorithms, or computer hardware.

---

### 2. What are the disadvantages of arrays?

a) Index value of an array can be negative  
b) Elements are sequentially accessed  
c) Data structure like queue or stack cannot be implemented  
d) There are chances of wastage of memory space if elements inserted in an array are lesser than the allocated size

**Answer:** d  
**Explanation:**  
Arrays are of fixed size. If we insert elements less than the allocated size, unoccupied positions can’t be used again. Wastage will occur in memory.

---

### 3. Which data structure is used for implementing recursion?

a) Stack  
b) Queue  
c) List  
d) Array

**Answer:** a  
**Explanation:**  
Stacks are used for the implementation of recursion.

---

### 4. The data structure required to check whether an expression contains a balanced parenthesis is?

a) Queue  
b) Stack  
c) Tree  
d) Array

**Answer:** b  
**Explanation:**  
The stack is a simple data structure in which elements are added and removed based on the LIFO principle. Open parenthesis is pushed into the stack and a closed parenthesis pops out elements till the top element of the stack is its corresponding open parenthesis. If the stack is empty, the parenthesis is balanced; otherwise, it is unbalanced.

---

### 5. Which of the following is not an application of a stack?

a) Data Transfer between two asynchronous processes  
b) Compiler Syntax Analyzer  
c) Tracking of local variables at runtime  
d) A parentheses balancing program

**Answer:** a  
**Explanation:**  
Data transfer between two asynchronous processes uses the queue data structure for synchronization. The rest are all stack applications.

---

### 6. Which data structure is needed to convert infix notation to postfix notation?

a) Tree  
b) Branch  
c) Stack  
d) Queue

**Answer:** c  
**Explanation:**  
The Stack data structure is used to convert infix expressions to postfix expressions. The purpose of the stack is to reverse the order of the operators in the expression. It also serves as a storage structure, as no operator can be printed until both of its operands have appeared.

---

### 7. What is the value of the postfix expression 6 3 2 4 + – \*?

a) 74  
b) -18  
c) 22  
d) 40

**Answer:** b  
**Explanation:**  
The postfix expression is equivalent to (6 \* (3 - (2 + 4))), which evaluates to -18.

---

### 8. What data structure would you most likely see in the non-recursive implementation of a recursive algorithm?

a) Stack  
b) Linked List  
c) Tree  
d) Queue

**Answer:** a  
**Explanation:**  
In recursive algorithms, the order in which the recursive process returns is the reverse of the order in which it proceeds. The stack data structure is used by the compiler to implement recursion. During execution, values like local variables, parameters, and return addresses are pushed to the stack, and they are popped during the return phase.

---

### 9. Which of the following statement(s) about stack data structure is/are NOT correct?

a) Top of the stack always contains the new node  
b) Stack is the FIFO data structure  
c) Null link is present in the last node at the bottom of the stack  
d) Linked lists are used for implementing stacks

**Answer:** b  
**Explanation:**  
Stack follows the Last In First Out (LIFO) principle, not FIFO.

---

### 10. The data structure required for Breadth First Traversal on a graph is?

a) Array  
b) Stack  
c) Tree  
d) Queue

**Answer:** d  
**Explanation:**  
In Breadth First Search (BFS), the starting vertex is taken, and unvisited adjacent vertices are processed. The queue data structure, which follows the First In First Out (FIFO) principle, is used for this traversal.

---

### 11. The prefix form of A-B/(C \* D ^ E) is?

a) -A/B*C^DE  
b) -A/BC*^DE  
c) -ABCD*^DE  
d) -/*^ACBDE

**Answer:** a  
**Explanation:**  
The infix expression A-B/(C*D^E) can be written as A-(B/(C*(D^E))). Its prefix form is -A/B\*C^DE.

---

### 12. Which of the following points is/are not true about Linked List data structure when it is compared with an array?

a) Random access is not allowed in a typical implementation of Linked Lists  
b) Access of elements in a linked list takes less time than compared to arrays  
c) Arrays have better cache locality that can make them better in terms of performance  
d) It is easy to insert and delete elements in Linked List

**Answer:** b  
**Explanation:**  
Accessing an element in a linked list requires traversal from the beginning to the desired position, which is slower than arrays that allow random access.

---

### 13. Which data structure is based on the Last In First Out (LIFO) principle?

a) Tree  
b) Linked List  
c) Stack  
d) Queue

**Answer:** c  
**Explanation:**  
The stack data structure follows the Last In First Out (LIFO) principle, making it suitable for specific order-based tasks.

---

### 14. Which of the following applications makes use of a circular linked list?

a) Recursive function calls  
b) Undo operation in a text editor  
c) Implement Hash Tables  
d) Allocating CPU to resources

**Answer:** d  
**Explanation:**  
Circular linked lists are used in allocating CPU time to processes in a round-robin fashion. Recursive function calls use stacks, undo operations use doubly linked lists, and hash tables use singly linked lists.

---

### 15. What is a bit array?

a) Data structure that compactly stores bits  
b) Data structure for representing arrays of records  
c) Array in which elements are not present in continuous locations  
d) An array in which most of the elements have the same value

**Answer:** a  
**Explanation:**  
A bit array compactly stores bits, exploiting bit-level parallelism for efficient processing.

---

### 16. Which of the following tree data structures is not a balanced binary tree?

a) Splay tree  
b) B-tree  
c) AVL tree  
d) Red-black tree

---

### 17. Which of the following is not the type of queue?

a) Priority queue  
b) Circular queue  
c) Single-ended queue  
d) Ordinary queue

**Answer:** c  
**Explanation:**  
A queue always has two ends. Therefore, a single-ended queue is not a valid queue type.

---

### 18. Which of the following data structures can be used for parentheses matching?

a) n-ary tree  
b) Queue  
c) Priority queue  
d) Stack

---

### 19. Which algorithm is used in the top tree data structure?

a) Backtracking  
b) Divide and Conquer  
c) Branch  
d) Greedy

**Answer:** b  
**Explanation:**  
The top tree data structure uses the divide-and-conquer algorithm and is designed for path-related problems using unrooted dynamic binary trees.

---

### 20. What is the need for a circular queue?

a) Easier computations  
b) Implement LIFO principle in queues  
c) Effective usage of memory  
d) To delete elements based on priority

**Answer:** c  
**Explanation:**  
A circular queue effectively utilizes memory by reusing dequeued positions, unlike a linear queue where such positions remain unutilized.

---

### 21. Which of the following is the most widely used external memory data structure?

a) B-tree  
b) Red-black tree  
c) AVL tree  
d) Both AVL tree and Red-black tree

**Answer:** a  
**Explanation:**  
B-trees are commonly used in external memory for their ability to store data values and pointers, optimizing block transfers.

---

### 22. Which of the following is also known as Rope data structure?

a) Linked List  
b) Array  
c) String  
d) Cord

**Answer:** d  
**Explanation:**  
The cord, also known as the rope data structure, is used for efficiently storing and manipulating long strings.

---

### 23. What will be the output of the following program?

```
main()

{
   char str[]="san foundry";
   int len = strlen(str);
   int i;

   for(i=0;i<len;i++)
        push(str[i]);  // pushes an element into stack

   for(i=0;i<len;i++)
      pop();  //pops an element from the stack
}

```

a) yrdnuof nas
b) foundry nas  
c) sanfoundry
d) san foundry

**Answer:** a
**Explanation:**  
First, the string ‘san foundry’ is pushed one by one into the stack.
When it is popped, the output will be as ‘yrdnuof nas’.
