# 🚀 Git & GitHub Learning Sandbox

[![Git](https://img.shields.shields.io/badge/Git-2.40+-F05032?style=for-the-badge&logo=git&logoColor=white)](https://git-scm.com/)
[![GitHub](https://img.shields.shields.io/badge/GitHub-Profile-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kartiksingh3066)
[![Terminal](https://img.shields.shields.io/badge/Shell-Git%20Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)]()

A hands-on environment dedicated to mastering local version control workflows, branch architectures, team collaboration simulation, and secure cloud authentication.

---

## 📌 Core Concepts Mastered

* **The Git Architecture:** Working fluidly across the *Working Directory*, *Staging Area*, and *Local Repository*.
* **Advanced Branching:** Creating isolated feature streams (`bug-fix`) and execution tracks.
* **Merge Architectures:** Executing both clean **Fast-Forward Merges** and advanced **3-Way Merges (with Merge Commits)**.
* **Conflict Resolution:** Manually auditing and handling parallel line-edit conflicts inside VS Code.
* **State Management:** Utilizing `git stash` to store, clear, and pop active workspaces seamlessly.
* **Cryptographic Auth:** Implementing **Ed25519 SSH key pairs** for passwordless, secure handshakes with GitHub.

---

## 🛠️ Commands Traveled

| Command | Category | Purpose |
| :--- | :--- | :--- |
| `git init` | Initialization | Starts a fresh tracking landscape |
| `git status` | Inspection | Audits tracked, modified, and staged files |
| `git add .` | Staging | Moves changes safely into the staging area |
| `git commit -m ""` | Recording | Locks in snapshots with isolated logs |
| `git log --graph` | Visualization | Renders visual commit trees in ASCII format |
| `git checkout -b` | Branching | Creates and instantly pivots to a new environment |
| `git merge` | Integration | Blends independent lines of development together |

---

## 📊 Git Visual Workflow

```text
  [ Working Directory ] ───( git add )───> [ Staging Area ]
           │                                      │
     (git restore)                           (git commit)
           ▼                                      ▼
     [ Unsaved Edits ]                     [ Local Repository ]
                                                  │
                                              (git push)
                                                  ▼
                                           [ GitHub Cloud]

# first commit in readme.md