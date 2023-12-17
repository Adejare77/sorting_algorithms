#!/bin/bash
Introduction to Sorting Algorithm (Time Complexity):

1. Bubble Sort:
    Time Complexity: O(n²)
    Description: Repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order. The pass through the list is repeated until the list is sorted.

2. Selection Sort:
    Time Complexity: O(n²)
    Description: Divides the input list into a sorted and an unsorted region. It repeatedly selects the smallest (or largest, depending on the ordering) element from the unsorted region and swaps it with the first element of the unsorted region.

3. Insertion Sort:
    Time Complexity: O(n²) (worst case), O(n) (best case)
    Description: Builds the final sorted array one element at a time. It takes each element from the unsorted part and inserts it into its correct position in the sorted part.

4. Quick Sort:
    Time Complexity: O(n log n) (average case), O(n²) (worst case)
    Description: Chooses a "pivot" element and partitions the array into two sub-arrays according to whether the elements are less than or greater than the pivot. The process is then applied recursively to each sub-array.

5. Merge Sort:
    Time Complexity: O(n log n)
    Description: Divides the unsorted list into n sub-lists, each containing one element, and repeatedly merges sub-lists to produce new sorted sub-lists until there is only one sub-list remaining, which is the sorted list.

6. Heap Sort:
    Time Complexity: O(n log n)
    Description: Builds a max-heap (or min-heap), which is a binary tree where the key of each node is greater (or smaller) than or equal to the keys of its children. The root element is then swapped with the last element, and the heap property is restored. This process is repeated until the entire list is sorted.
