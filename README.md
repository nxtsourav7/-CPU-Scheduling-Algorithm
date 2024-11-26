# CPU Scheduling Algorithm

Welcome to the **Scheduling Algorithms Repository**! This repository contains implementations of various CPU scheduling algorithms, written in C++. These algorithms are fundamental for understanding process scheduling in operating systems.

## 🚀 Features

- Implementation of widely used CPU scheduling algorithms.
- Includes key metrics like:
  - **Completion Time (CT)**
  - **Turnaround Time (TAT)**
  - **Waiting Time (WT)**
  - **Response Time (RT)**
- Easy-to-understand, modular code.
- Suitable for academic purposes and hands-on learning.

---

## 📂 Algorithms Implemented

| Algorithm                         | Description                                                                                 |
|-----------------------------------|---------------------------------------------------------------------------------------------|
| **First Come, First Serve (FCFS)** | Processes are executed in the order of their arrival. Non-preemptive scheduling.            |
| **Shortest Job Next (SJN)**       | Executes the process with the shortest burst time next. Non-preemptive scheduling.          |
| **Shortest Remaining Time (SRTF)**| Preemptive version of SJN, prioritizing processes with the shortest remaining burst time.    |
| **Round Robin (RR)**              | Time-sharing scheduling where each process gets a fixed time quantum.                      |
| **Priority Scheduling**           | Processes are prioritized based on a given priority value. Both preemptive and non-preemptive.|
| **Multi-Level Queue**             | Processes are divided into categories with different scheduling policies per queue.        |

---

## 📊 Metrics Explained

Each algorithm outputs the following metrics for better analysis:

- **Completion Time (CT)**: When the process finishes execution.
- **Turnaround Time (TAT)**: \( TAT = CT - AT \), total time from arrival to completion.
- **Waiting Time (WT)**: \( WT = TAT - BT \), time spent in the waiting queue.
- **Response Time (RT)**: Time from arrival to the first CPU allocation.

---

## 🔧 How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/scheduling-algorithms.git
   cd scheduling-algorithms
