# Datastructures-and-Algorithms

### What is Datastructure?

Datastructures is way to organize data in a way that enables it to be processed in efficient time

1. Array
2. Linked List
3. Stack
4. Queue
5. Tree
6. Hashing
7. Graph.etc

Two types are datastructures

1. Primitive datastructure (Integer, Float, Boolean and Character)
2. Non primitive datastructure

   * Physical DS
     * Array
     * Linked List

     - Physical datastructures are standalone and it present in the memory

   * Logical DS 
     * Stack
     * Queue
     * Tree
     * Graph

     - These are logical in nature, These are all depends on the phsical datastructures

#### Recursion     

  Function that calls itself during its execution.

Behaviour of recursion
 * Performs a certain operation multiple times
 * In each iteration problem will get smaller
 * Mandatory need to have base condition, Which tells to stop the recurrsion

 Usage: Lets say we need to find a value, In a binary tree

 Why we know recusion:

 - It is easy to write, given problem can be broken into similar sub-problem

 When to use?

 - When we can broken down a problem into similar sub-problem 
 - Datastructures like tree, Graph, etc.
 - To use and understand techniques like Divide and Conquer, Greedy, Dynamic programming

 Format of recursive function:

 - Recursive case: Case where the function need to recur
 - Base case : case where the function does not recur

 Ex: 

   ```
   function SampleRecusion(parameter) {
     if(base case is satisfied) {
       return some base case value
     } else {
       SampleRecusion(modifiedParameter)
     }
   }
   ```

### What is algorithms?

Algorithms are set of rules that to be followed to solve a problem
