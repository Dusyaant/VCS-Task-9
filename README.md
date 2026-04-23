# VCS Task 9: Version Control Systems & Advanced Git Workflow

This repository documents the implementation of a structured Version Control workflow using Git and GitHub. The project focuses on demonstrating mastery over branching strategies, history management, and real-world conflict resolution.

## 🚀 Tasks Implemented

### 1. Repository Lifecycle Management
- Established a local Git environment and synchronized it with the remote GitHub repository.
- Managed two core Python scripts (`script1.py`, `script2.py`) representing project modules.

### 2. Advanced Git Operations
- **Git Stash**: Demonstrated context switching by temporarily shelving uncommitted changes, allowing for a clean working directory transition.
- **Branching & Merging**: Created dedicated feature branches to isolate development, followed by a controlled merge into the `main` branch.
- **Git Rebase**: Utilized rebasing to maintain a linear and clean project history, ensuring commits are logically ordered.

### 3. Conflict Resolution
- Handled a manual **Merge Conflict** in `script2.py` during the rebase phase.
- Resolved the conflict by integrating divergent code paths and finalizing the rebase using `git rebase --continue`.

## 📁 Project Structure

| File | Description |
| :--- | :--- |
| `script1.py` | Primary application logic (Python). |
| `script2.py` | Secondary module utilized for branch testing. |
| `Git_History.png` | Visual proof of the commit graph and branching structure. |
| `Command_Reflog.png` | Detailed history of all terminal commands (merges, rebases, checkouts). |
| `Remote_Config.png` | Evidence of successful remote repository linkage. |
| `Final_Status.png` | Confirmation of a clean working tree and up-to-date sync. |

## 🛠️ Key Commands Used
- `git init` / `git remote add`
- `git stash` / `git stash pop`
- `git checkout -b <branch>`
- `git rebase main`
- `git log --oneline --graph --all`

## 👨‍💻 Author
**Dusyaant R** Specialization: Cybersecurity  
SIMATS Engineering
