Heap Sort Algorithm Assignment

Name: jonas Malwa

Registration Number
EB3/67265/23


Project Description

This project implements the Heap Sort algorithm in C++ to sort a list of integers without using any built-in sorting functions.

The program accepts an unsorted list of numbers, sorts them in ascending order, and displays the sorted list along with the total number of comparisons and swaps performed during the sorting process.

---

Sorting Algorithm Used

Heap Sort

Heap Sort is a comparison-based sorting algorithm that uses a binary heap data structure.
It works by first converting the array into a max heap, where the largest element is placed at the root. The root element is then swapped with the last element of the heap, and the heap size is reduced. This process continues until the array is completely sorted.

---

How the Algorithm Works

1. Build a max heap from the input data.
2. The largest element will be at the root of the heap.
3. Swap the root element with the last element.
4. Reduce the heap size by one.
5. Heapify the root again to restore heap order.
6. Repeat until all elements are sorted.

---

Example Demonstration

Example input list:

4, 10, 3, 5, 1

Step 1 – Build max heap:

10, 5, 3, 4, 1

Step 2 – Swap root with last element:

1, 5, 3, 4, 10

Step 3 – Heapify again:

5, 4, 3, 1, 10

Continue until sorted result:

1, 3, 4, 5, 10

---

Time Complexity

Best Case:
O(n log n)

Average Case:
O(n log n)

Worst Case:
O(n log n)

Explanation:
Heap operations take logarithmic time, and the algorithm processes all elements.

---

Space Complexity

O(1)

The algorithm sorts the list in place, meaning no extra memory is required apart from a few variables.

---

Experiment Results

The algorithm was tested using different input sizes:

1
2
3
4
5
10
250
999
9999
89786
789300
1780000

For each test, the program recorded the number of comparisons and swaps.

(You can include a table here if required.)

---

Repository Contents

HeapSort.cpp – C++ implementation of the Heap Sort algorithm
README.md – Documentation and explanation of the project

---

Conclusion

Heap Sort is an efficient sorting algorithm with a consistent time complexity of O(n log n). It performs well for large datasets and does not require additional memory.
