# CPU Scheduling Algorithms

This project demonstrates core CPU scheduling algorithms implemented in [your language/tool here, e.g., Python, Java, etc.]. It includes visual representations using Gantt charts and showcases team collaboration using Git.

---

## 📘 Scheduling Algorithms Explained

### 🔹 First Come First Serve (FCFS)

- **Definition**: Processes are executed in the order they arrive.
- **Characteristics**:
  - Non-preemptive
  - Simple to implement
  - Can result in long average waiting times if short processes are stuck behind long ones.

### 🔹 Shortest Job First (SJF)

- **Definition**: Executes the process with the shortest burst time first.
- **Characteristics**:
  - Can be preemptive or non-preemptive
  - Lower average waiting time
  - Requires knowledge of burst times in advance

### 🔹 Round Robin (RR)

- **Definition**: Each process is given a fixed time quantum and is cycled through in a queue.
- **Characteristics**:
  - Preemptive
  - Fair to all processes
  - Performance depends on the size of the time quantum

---

## 📊 Gantt Charts

### 🟦 FCFS Example

| Process | Start Time | End Time |
|---------|------------|----------|
| P1      | 0          | 5        |
| P2      | 5          | 9        |
| P3      | 9          | 14       |

### 🟪 SJF Example

| Process | Start Time | End Time |
|---------|------------|----------|
| P2      | 0          | 2        |
| P1      | 2          | 7        |
| P3      | 7          | 12       |

### 🟨 RR Example (Time Quantum = 2)

| Time | Process |
|------|---------|
| 0-2  | P1      |
| 2-4  | P2      |
| 4-6  | P3      |
| 6-8  | P1      |
| 8-10 | P2      |
| 10-11| P3      |

<img width="1365" height="689" alt="image" src="https://github.com/user-attachments/assets/f4c54c46-6811-4b1e-bea5-09ace7fd0ec6" />
<img width="1348" height="696" alt="image" src="https://github.com/user-attachments/assets/69591365-b074-4ed3-bc19-5a6bcc9ec0c1" />
<img width="1363" height="598" alt="image" src="https://github.com/user-attachments/assets/85edd69f-c612-4171-ab82-254a182f8cd8" />



