# Big-O Complexity Analysis

## Searching Algorithms

| Algorithm | Best | Average | Worst |
|---|---|---|---|
| Linear Search | O(1) | O(n) | O(n) |
| Binary Search | O(1) | O(log n) | O(log n) |

Binary Search requires sorted data. Linear Search works on unsorted records.

## Sorting Algorithms

| Algorithm | Best | Average | Worst |
|---|---|---|---|
| Bubble Sort | O(n) if optimized; otherwise O(n²) | O(n²) | O(n²) |
| Selection Sort | O(n²) | O(n²) | O(n²) |
| Insertion Sort | O(n) | O(n²) | O(n²) |

Bubble Sort's O(n) best case requires an early-exit optimization.

## Data Structures

| Operation | Time Complexity |
|---|---|
| Doubly Linked List search | O(n) |
| Doubly Linked List insertion at known position | O(1) |
| Doubly Linked List deletion of known node | O(1) |
| Stack push/pop | O(1) |
| Circular Queue enqueue/dequeue | O(1) |
| Linked Priority Queue enqueue | O(n) |
| Linked Priority Queue dequeue | O(1) |

The listed linked-list insertion and deletion costs assume the relevant node or position is already known. Searching for that position may add O(n).

## Actual Benchmark Results

Random data, 1,000 records:

| Algorithm | Execution Time |
|---|---:|
| Bubble Sort | 13.644 ms |
| Selection Sort | 1.280 ms |
| Insertion Sort | 4.887 ms |

In these individual runs, Selection Sort had the lowest recorded execution time. Theoretical Big-O describes how running time grows with input size, not the exact runtime of a single test.
