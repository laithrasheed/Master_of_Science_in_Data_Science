# Algorithms for Searching, Sorting, and Indexing[<sup>[1]</sup>](#reference-1)				

## Brief Description
- This course covers basics of algorithm design and analysis, as well as algorithms for sorting arrays, data structures such as priority queues, hash functions, and applications such as Bloom filters.

## Prior knowledge needed: 

### Mathematical Background: 
We expect that the student is comfortable with basic mathematics at the level of a U.S. first-year college STEM student. This includes basic notions such as sets and functions: Properties of sets, definition and properties of functions; logarithms and exponentials: and their properties; basic series summations: arithmetic and geometric series summations; and probability theory: basic definition of probability, independence of events, probability distributions and expectations.  CLRS has a helpful appendix but the student unfamiliar with these concepts can find numerous high quality explanations online.

### Programming Background: 
The course involves solving programming assignments in Python. You must be comfortable with Python programming. This includes basic control structures in Python: conditional branches, for loops and recursion; functions: defining and calling functions, and recursion; in-built data structures: lists and dictionaries; and classes. Our use of Python will get more sophisticated as the course progresses to accommodate some learning of Python. 

## Resources
- Introduction to Algorithms by CLRS
- [Algorithm by Prof. Jeff Erickson](https://jeffe.cs.illinois.edu/teaching/algorithms/)

## Course Content

### Week 1 | Basics of Algorithms Through Searching and Sorting

In this module the student will learn the very basics of algorithms through three examples: insertion sort (sort an array in ascending/descending order); binary search: search whether an element is present in a sorted array and if yes, find its index; and merge sort (a faster method for sorting an array). Through these algorithms the student will be introduced to the analysis of algorithms -- i.e., proving that the algorithm is correct for the task it has been designed for and establishing a bound on how the time taken to execute the algorithm grows as a function of input. The student is also exposed to the notion of a faster algorithm and asymptotic complexity through the O, big-Omega and big-Theta notations.

#### Learning Objectives
- Analyze computational complexity of algorithms.
- Prove correctness of algorithms using inductive invariants.
- Analyze the running time of binary search, insertion sort, bubble sort and merge sort algorithms.
- Prove correctness of binary search, insertion sort, bubble sort and merge sort algorithms.
- Compare running time of algorithms through big-O, big-Omega and big-Theta notations

#### Programming Assignment
- [Introductions to Algorithms](https://github.com/laithrasheed/MSDS_Program_Private/blob/main/Data%20Science%20Foundations/Data%20Structures%20and%20Algorithms/1-Algorithms%20for%20Searching%20Sorting%20and%20Indexing/M1-Introduction-to-Algorithms.ipynb)

### Week 2 | Heaps and Hashtable Data Structures

In this module, the student will learn about the basics of data structures that organize data to make certain types of operations faster. The module starts with a broad introduction to data structures and talks about some simple data structures such as first-in first out queues and last-in first out stack. Next, we introduce the heap data structure and the basic properties of heaps. This is followed by algorithms for insertion, deletion and finding the minimum element of a heap along with their time complexities. Finally, we will study the priority queue data structure and showcase some applications.

#### Learning Objectives
- Understand the need for data structures and how these are used in programming.
- Define the properties of a min/max heap and reason about the implication of these properties.
- Analyze the correctness and running time of insertion, deletion and find minimum/maximum operations on a heap.
- Identify problems that can be solved efficiently using heaps and problems where heaps may be a sub-optimal choice.
- Understand hashtable data structure, its organization and properties.
- Learn the basic differences between a heap and a hashtable data-structure. Understand when to use a hashtable as opposed to a heap data-structure

#### Programming Assignment
- [Heap Data Structures](https://github.com/laithrasheed/MSDS_Program_Private/blob/main/Data%20Science%20Foundations/Data%20Structures%20and%20Algorithms/1-Algorithms%20for%20Searching%20Sorting%20and%20Indexing/M2-Heap-Data-Structures.ipynb)

### Week 3 | Randomization: Quicksort, Quickselect, and Hashtables

We will go through the quicksort and quickselect algorithms for sorting and selecting the kth smallest element in an array efficiently. This will also be an introduction to the role of randomization in algorithm design. Next, we will study hashtables: a highly useful data structure that allows for efficient search and retrieval from large amounts of data. We will learn about the basic principles of hash-table and operations on hashtables.

#### Learning Objectives
- Understand and implement quicksort algorithm with a carefully designed partition scheme.
- Prove correctness of the partition scheme and the algorithm.
- Understand and implement the quickselect algorithm.
- Perform an empirical evaluation of running time for quicksort and quickselect algorithms
- Understand the pitfalls behind hash function design for hashtables and the use of randomization to make hashtables work against the worst case.

#### Programming Assignment
- [Quicksort and Hash Functions](https://github.com/laithrasheed/MSDS_Program_Private/blob/main/Data%20Science%20Foundations/Data%20Structures%20and%20Algorithms/1-Algorithms%20for%20Searching%20Sorting%20and%20Indexing/M3-Quicksort-and-Hash-Functions.ipynb)

### Week 4 | Advanced Topics

In this module, we will learn randomized pivot selection for quicksort and quickselect. We will learn how to analyze the complexity of the randomized quicksort/quickselect algorithms. We will learn open address hashing: a technique that simplifies hashtable design. Next we will study the design of hash functions and their analysis. Finally, we present and analyze Bloom filters that are used in various applications such as querying streaming data and counting.

#### Learning Objectives
- Design open-address hash-tables and algorithms for insertion and deletion.
- Cuckoo hashing, double hashing and variants.
- Bloom filters and their applications
- Understand how to use hash-tables for sketching over streaming data.

#### Programming Assignment
- [Hash Applications](https://github.com/laithrasheed/MSDS_Program_Private/blob/main/Data%20Science%20Foundations/Data%20Structures%20and%20Algorithms/1-Algorithms%20for%20Searching%20Sorting%20and%20Indexing/M4-Hash-Applications.ipynb)

### Week 5 | Final Exam

You will complete a programming assignment worth 16% of your grade. You must attempt the final in order to earn a grade in the course. If you've upgraded to the for-credit version of this course, please make sure you review the additional for-credit materials in the Introductory module and anywhere else they may be found.

#### Learning Objectives
- Demonstrate mastery of the material presented in this course.

#### Programming Assignment
- [Final Exam](https://github.com/laithrasheed/MSDS_Program_Private/blob/main/Data%20Science%20Foundations/Data%20Structures%20and%20Algorithms/1-Algorithms%20for%20Searching%20Sorting%20and%20Indexing/M5-Final-Exam.ipynb)

## References
###### <a name="reference-1"></a>[[1] Course Curriculum - Master of Science in Data Science - University of Colorado Boulder](https://www.colorado.edu/program/data-science/coursera/curriculum/dtsa5501)
