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

🧭 1. Fork and Clone the Repository (if you're not the owner)

If you're contributing to someone else's project:

# Fork it on GitHub, then clone your fork:
git clone https://github.com/your-username/project-name.git
cd project-name


If it's a shared team repo and you have write access:

git clone https://github.com/team-name/project-name.git
cd project-name

🌿 2. Create a Feature Branch

Always create a new branch before making changes:

git checkout -b feature/algorithm-update


This keeps your work separate from the main branch, helping to avoid conflicts.

💻 3. Make Changes and Commit

Edit files (e.g., add code, update README, fix bugs), then stage and commit:

git add .
git commit -m "Implement Round Robin scheduling algorithm"


✅ Good commit messages explain what and why, e.g.,
"Fix FCFS waiting time calculation" or
"Add Gantt chart visualisation for SJF"

🚀 4. Push Your Branch to GitHub
git push origin feature/algorithm-update


This uploads your branch to the GitHub repo.

🔃 5. Open a Pull Request (PR)

Go to the GitHub repository.

You’ll see a prompt: "Compare & pull request" – click it.

Add a meaningful title and description.

Assign reviewers if needed.

Click "Create Pull Request".

💡 Pull Requests allow others to review your code before merging.

🔁 6. Fetch and Pull Updates Regularly

Before making new changes, always sync with the main branch to avoid conflicts:

git checkout main
git pull origin main


Then rebase or merge into your feature branch:

git checkout feature/algorithm-update
git merge main
# OR
git rebase main

✅ 7. Merge the Pull Request

Once reviewed and approved:

Click "Merge Pull Request" on GitHub.

Optionally delete the branch after merging.

Then pull changes to your local machine:

git checkout main
git pull origin main

📸 8. Add Screenshots (Optional but Helpful)

You can document your collaboration visually in the README.md:

### Example: Commit Screenshot
![Commit Screenshot](screenshots/commit.png)

### Example: Pull Request Screenshot
![PR Screenshot](screenshots/pull_request.png)

### Example: Merge Screenshot
![Merge Screenshot](screenshots/merge.png)


