# Technical Test

### First Test: Algorithm Implementation - Merge Sort

#### Task Description
You are given an array of integers. The task is to implement the `merge_sort()` function that sorts the array using the Merge Sort algorithm.

#### Problem Statement
- **Input**: An array of integers, where 1 ≤ arr.length ≤ 10^5, and -10^5 ≤ arr[i] ≤ 10^5.
- **Output**: A sorted array of integers.

#### Solution
Merge Sort is a divide-and-conquer algorithm that splits the array into smaller subarrays, sorts them, and merges them back together. Here’s a high-level overview of how the algorithm works:

1. **Divide** the array into two halves.
2. **Recursively sort** each half.
3. **Merge** the sorted halves to produce the final sorted array.
