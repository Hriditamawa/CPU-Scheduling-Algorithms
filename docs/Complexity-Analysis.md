# CPU Scheduling Algorithms – Complexity Analysis

This document provides a theoretical comparison of the time and space complexity of the five CPU scheduling algorithms.

## 1. Complexity Comparison

Let `n` represent the total number of processes.

| Algorithm | Typical Time Complexity | Space Complexity |
|---|---|---|
| FCFS | O(n log n) with sorting; O(n) if already ordered | O(n) |
| SJF | O(n log n) with sorting | O(n) |
| Priority Scheduling | O(n log n) with sorting | O(n) |
| Round Robin | O(n × k) | O(n) |
| Multilevel Queue | Depends on queue scheduling policies | O(n) |

Here, `k` represents the number of scheduling rounds required by Round Robin.

## 2. Algorithm Analysis

### FCFS
Processes can be executed in arrival order. If sorting is required, the sorting operation generally takes O(n log n) time.

### SJF
Selecting processes based on burst time may require sorting. A typical comparison-based sorting approach takes O(n log n) time.

### Priority Scheduling
Processes may be ordered according to priority. Comparison-based sorting generally takes O(n log n) time.

### Round Robin
Each process receives CPU time in repeated scheduling rounds. The total cost depends on the number of rounds and the queue implementation.

### Multilevel Queue
Its complexity depends on the number of queues, the scheduling policy used in each queue, and the method used to schedule between queues.

## 3. Important Note

These are typical theoretical estimates, not guaranteed measurements of the uploaded C programs. Actual complexity depends on the implementation, data structures, sorting method, and scheduling policy.
