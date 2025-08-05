# Topic: Heap Data Structure

### : Definition of Heap
- What is a Heap?
  - A heap is a specialized tree-based data structure that satisfies the heap property, commonly used for priority queues and sorting algorithms.

  - : Heap Properties
    - What are the key properties of a Heap?
      - The two key properties are: 
        1) Complete Binary Tree structure
        2) Heap Order Property (either Min-Heap or Max-Heap)
  
  - : Complete Binary Tree
    - What is a Complete Binary Tree?
      - A binary tree where all levels are fully filled except possibly the last level, which is filled from left to right.

  - : Heap Order Property
    - What is the Heap Order Property?
      - For Max-Heap: Parent nodes are greater than or equal to child nodes
      - For Min-Heap: Parent nodes are less than or equal to child nodes

### : Types of Heaps
- What are the main types of Heaps?
  - The main types are:
    1) Binary Heap
    2) Binomial Heap
    3) Fibonacci Heap
    4) Min-Heap
    5) Max-Heap

  - : Binary Heap
    - What is a Binary Heap?
      - A binary heap is a complete binary tree that satisfies the heap property, typically implemented as an array.


### : Binary Heap Implementation
- How is a Binary Heap implemented?
  - Using an array where for any node at index i:
    - Left child: 2i + 1
    - Right child: 2i + 2
    - Parent: floor((i-1)/2)

### : Min-Heap vs Max-Heap
- What is the difference between Min-Heap and Max-Heap?
  - Min-Heap: Root is the minimum element
  - Max-Heap: Root is the maximum element

### : Heap Operations
- What are the basic Heap operations?
  - The fundamental operations are:
    1) Insertion
    2) Deletion (Extract-Min/Extract-Max)
    3) Heapify
    4) Peek (Find-Min/Find-Max)

#### : Insertion
- How does insertion work in a Heap?
  - 1) Add element at the next available position
  - 2) Bubble up (Heapify Up) until heap property is restored

#### : Deletion
- How does deletion work in a Heap?
  - 1) Remove root element
  - 2) Move last element to root
  - 3) Bubble down (Heapify Down) until heap property is restored

#### : Heapify
- What is Heapify?
  - The process of converting a binary tree into a heap by adjusting nodes to satisfy the heap property.

##### : Time Complexity of Heapify
- What is the time complexity of Heapify?
  - O(log n) for single operation
  - O(n) for building a heap from an unordered array

### : Applications of Heap
- Where are Heaps commonly used?
  - Priority Queues
  - Heap Sort algorithm
  - Graph algorithms (Dijkstra's, Prim's)
  - Order statistics

#### : Priority Queue
- How is Heap used in Priority Queues?
  - Provides O(1) access to min/max element and O(log n) insertion/deletion

#### : Heap Sort
- How does Heap Sort work?
  - 1) Build a Max-Heap from the array
  - 2) Repeatedly extract the maximum element
  - 3) Results in sorted array in O(n log n) time

### : Heap vs Other Structures
- How does Heap compare to other data structures?

#### : Heap vs Binary Search Tree
- What's the difference between Heap and BST?
  - Heap: Only guarantees parent-child order, not left-right order
  - BST: Maintains sorted order between left and right children

#### : Heap vs Array
- When to use Heap over Array?
  - When frequent min/max access is needed
  - When dynamic priority-based access is required
