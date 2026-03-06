# Merge Sort Program (C++)

## Overview

This program demonstrates the implementation of the **Merge Sort algorithm** in C++. The program accepts integers from the user, sorts them using merge sort, and displays the sorted output.

Merge Sort is a **divide-and-conquer algorithm** that works by repeatedly dividing the array into smaller parts, sorting them, and then merging them back together in the correct order.

---

## Features

* Accepts a user-defined number of integers
* Sorts the integers using the Merge Sort algorithm
* Displays the sorted result
* Demonstrates recursion and array manipulation

---

## How the Program Works

### 1. Input

The user is asked to enter:

* The number of elements
* The integers to be sorted

Example input:

```
Enter number of elements: 5
Enter integers:
5 2 9 1 6
```

---

### 2. Divide Phase

The array is divided into two halves repeatedly until each subarray contains only one element.

Example:

```
[5, 2, 9, 1]

Split into:
[5, 2] and [9, 1]

Split again:
[5] [2] [9] [1]
```

---

### 3. Merge Phase

The single-element arrays are merged back together in sorted order.

Example:

```
[5] + [2]  →  [2,5]
[9] + [1]  →  [1,9]

Final merge:
[2,5] + [1,9] → [1,2,5,9]
```

---

## Algorithm Steps

1. If the array contains more than one element, find the middle point.
2. Divide the array into two halves.
3. Recursively apply merge sort to each half.
4. Merge the sorted halves back into one sorted array.

---

## Time Complexity

| Case         | Complexity |
| ------------ | ---------- |
| Best Case    | O(n log n) |
| Average Case | O(n log n) |
| Worst Case   | O(n log n) |

---

## Space Complexity

Merge sort requires additional memory for temporary arrays during the merge process.

```
Space Complexity: O(n)
```

---

## Sample Output

```
Enter number of elements: 5
Enter integers:
5
```
