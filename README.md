# CPU Scheduling Algorithms in C

A practical implementation of five fundamental CPU scheduling algorithms using the C programming language. This project explores how operating systems manage process execution and allocate CPU time efficiently.

## 📌 Project Overview

CPU scheduling is an essential function of an operating system. It determines which process gets access to the CPU and for how long.

This repository contains implementations of five commonly studied CPU scheduling algorithms, along with their source code and practical examples.

## 🚀 Implemented Algorithms

| No. | Algorithm | Description |
|---|---|---|
| 01 | FCFS | First Come First Serve |
| 02 | SJF | Shortest Job First |
| 03 | Priority Scheduling | Execution based on process priority |
| 04 | Round Robin | Time-quantum-based scheduling |
| 05 | Multilevel Queue | Scheduling using multiple process queues |

## 📂 Project Structure

```text
CPU-Scheduling-Algorithms/
│
├── README.md
│
└── src/
    ├── README.md
    ├── FCFS.c
    ├── SJF.c
    ├── Priority.c
    ├── RoundRobin.c
    └── MultilevelQueue.c
```

## 🛠️ Technologies Used

- Programming Language: C
- Compiler: GCC
- Development Environment: Code::Blocks / VS Code

## ⚙️ How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/YOUR-USERNAME/CPU-Scheduling-Algorithms.git
   ```

2. Navigate to the source directory:

   ```bash
   cd CPU-Scheduling-Algorithms/src
   ```

3. Compile an algorithm:

   ```bash
   gcc FCFS.c -o FCFS
   ```

4. Run the program:

   ```bash
   ./FCFS
   ```

   On Windows:

   ```bash
   FCFS.exe
   ```

## 🎯 Learning Objectives

- Understand fundamental CPU scheduling concepts.
- Implement scheduling algorithms using C.
- Explore process execution order and CPU allocation.
- Practice algorithmic problem-solving.
- Compare different CPU scheduling strategies.

## 👩‍💻 Author

**Hridi**

## 📚 Academic Project

Developed as part of Operating Systems coursework.

---

*Learning, implementing, and understanding how operating systems work — one algorithm at a time.*
