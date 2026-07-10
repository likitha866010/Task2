# Algorithms & Problem Solving (Sorting / Greedy)

## Project Overview

This project demonstrates the implementation of fundamental algorithms used in problem solving. It includes algorithms for sorting and optimization using the Greedy approach. The programs are written in C/C++ and are designed to be simple, efficient, and easy to understand.

## Algorithms Implemented

### 1. Quicksort
Quicksort is a divide-and-conquer sorting algorithm that recursively partitions an array around a pivot element and sorts the resulting subarrays.

**Features**
- Recursive implementation
- Efficient average-case performance
- In-place sorting

**Time Complexity**
| Case | Complexity |
|------|------------|
| Best | O(n log n) |
| Average | O(n log n) |
| Worst | O(n²) |

**Space Complexity**
- O(log n) (Recursive stack)

---

### 2. 0/1 Knapsack
The 0/1 Knapsack problem is solved using Dynamic Programming to determine the maximum profit without exceeding the given weight capacity.

**Features**
- Dynamic Programming approach
- Calculates maximum achievable profit
- Efficient for moderate input sizes

**Time Complexity**
- O(n × W)

where:
- n = Number of items
- W = Knapsack capacity

**Space Complexity**
- O(n × W)

---

## Project Structure

```
Task2/
│
├── Quicksort/
│   ├── quicksort.c
│
├── Knapsack/
│   ├── knapsack.c
└── README.md
```

---

## Compilation

### Quicksort

```bash
g++ quicksort.cpp -o quicksort
./quicksort
```

### Knapsack

```bash
g++ knapsack.c -o knapsack
./knapsack
```

For Windows (MinGW)

```bash
g++ quicksort.c -o quicksort.exe
quicksort.exe

g++ knapsack.c -o knapsack.exe
knapsack.exe
```

---

## Sample Output

### Quicksort

```
Original Array:
10 7 8 9 1 5

Sorted Array:
1 5 7 8 9 10
```

---

### Knapsack

```
Maximum Profit = 220
Runtime = 0.000000 seconds
```

---

## Runtime Analysis

The runtime of each algorithm can be measured using the built-in timing functions.

Example observations:

| Algorithm | Input Size | Runtime |
|-----------|-----------|---------|
| Quicksort | 100 | Very Fast |
| Quicksort | 1000 | Fast |
| Quicksort | 10000 | Moderate |
| Knapsack | Small | Very Fast |
| Knapsack | Medium | Fast |
| Knapsack | Large | Increases with capacity |

---

## Concepts Demonstrated

- Divide and Conquer
- Dynamic Programming
- Sorting Algorithms
- Optimization Problems
- Time Complexity Analysis
- Runtime Measurement

---

## Technologies Used

- C
- GCC / G++
- Visual Studio Code
