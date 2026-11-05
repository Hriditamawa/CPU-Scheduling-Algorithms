# CPU Scheduling Algorithms – Explanation

This document explains the working principles of the five CPU scheduling algorithms implemented in this project.

## 1. First Come First Serve (FCFS)

FCFS is a non-preemptive scheduling algorithm. Processes are executed in the order they arrive in the ready queue.

**Key Characteristics:**
- Simple and easy to implement.
- Uses a FIFO scheduling approach.
- A process cannot be interrupted once execution begins.
- May cause the Convoy Effect.

## 2. Shortest Job First (SJF)

SJF selects the process with the shortest CPU burst time for execution.

**Key Characteristics:**
- Can be implemented in preemptive or non-preemptive form.
- Often provides a lower average waiting time.
- Requires knowledge or estimation of CPU burst time.
- Long processes may experience starvation.

## 3. Priority Scheduling

Priority Scheduling assigns a priority value to each process. The CPU is allocated to the process with the highest priority according to the implementation's priority convention.

**Key Characteristics:**
- Supports preemptive and non-preemptive implementations.
- Useful when processes have different levels of importance.
- Low-priority processes may experience starvation.
- Aging can help prevent starvation.

## 4. Round Robin (RR)

Round Robin is a preemptive scheduling algorithm in which each process receives a fixed amount of CPU time called a time quantum.

**Key Characteristics:**
- Processes execute in a circular queue.
- Each process receives a fair share of CPU time.
- Suitable for time-sharing systems.
- Performance depends on the selected time quantum.

## 5. Multilevel Queue Scheduling (MQS)

Multilevel Queue Scheduling divides the ready queue into multiple separate queues based on process categories or priorities.

**Key Characteristics:**
- Each queue may use a different scheduling algorithm.
- Processes are assigned to specific queues.
- Scheduling between queues follows a defined priority or time-sharing policy.
- Lower-priority queues may experience starvation.

---

**Note:** The exact behavior of each algorithm depends on its implementation in the source code.
