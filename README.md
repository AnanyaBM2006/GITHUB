# 🛠️ Git  Guide
> A comprehensive guide to understanding Version Control and essential Git commands.

---

## 📖 What is Git?
Git is a **Distributed Version Control System (DVCS)**. It tracks changes in your source code during software development. Unlike older systems, Git allows every developer to have a full copy of the project history on their local machine.

* **Speed:** Almost all operations are local.
* **Integrity:** Everything is checksummed before being stored.
* **Branching:** Powerful tools to work on features independently.



---

## 🔄 The Basic Workflow
Most Git work follows a standard 3-step cycle:

1.  **Modify:** Change files in your working directory.
2.  **Stage:** Mark the changes as ready (using `git add`).
3.  **Commit:** Save the snapshot to the database (using `git commit`).

---

## 🚀 Essential Commands

| Command | Description |
| :--- | :--- |
| `git init` | Initializes a new local Git repository. |
| `git clone <url>` | Downloads an existing project from a remote source. |
| `git status` | Shows the state of the working directory and staging area. |
| `git add .` | Adds all current changes to the staging area. |
| `git commit -m "msg"` | Commits the staged snapshot with a descriptive message. |
| `git push` | Uploads local repository content to a remote repository. |
| `git pull` | Fetches and merges changes from the remote to local. |
| `git branch` | Manages your branches (create, list, or delete). |

---

## 💡 How to use it
To start a project from scratch:
1. `git init`
2. Create your files.
3. `git add .`
4. `git commit -m "Initial commit"`
