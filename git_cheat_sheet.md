## 🖥️ Git and GitHub Commands

### 1. **Git Basics**
| Command                           | Description                                                                 |
|-----------------------------------|-----------------------------------------------------------------------------|
| `git init`                        | Initialize a new Git repository.                                            |
| `git clone [url]`                 | Clone a remote repository to your local machine.                            |
| `git status`                      | Check the status of your repository (tracked/untracked files, changes, etc.).|
| `git add [file]`                  | Stage changes for commit.                                                   |
| `git commit -m "[message]"`       | Commit staged changes with a descriptive message.                           |
| `git log`                         | View commit history.                                                        |

### 2. **Working with Branches**
| Command                           | Description                                                                 |
|-----------------------------------|-----------------------------------------------------------------------------|
| `git branch`                      | List branches or create a new branch.                                       |
| `git checkout [branch_name]`       | Switch to an existing branch.                                               |
| `git checkout -b [branch_name]`    | Create and switch to a new branch.                                          |
| `git merge [branch_name]`          | Merge a branch into the current branch.                                     |
| `git rebase [branch_name]`         | Rebase the current branch onto another branch (rebase history).             |

### 3. **Undoing Changes**
| Command                           | Description                                                                 |
|-----------------------------------|-----------------------------------------------------------------------------|
| `git reset [commit]`              | Undo commits while keeping local changes (soft reset).                      |
| `git reset --hard [commit]`       | Completely undo commits and discard changes (hard reset).                   |
| `git revert [commit]`             | Create a new commit that undoes a previous commit without modifying history. |

### 4. **Pushing and Pulling**
| Command                           | Description                                                                 |
|-----------------------------------|-----------------------------------------------------------------------------|
| `git push origin [branch]`        | Push local commits to the remote repository.                                |
| `git pull`                        | Fetch and merge changes from the remote repository.                         |
| `git fetch`                       | Fetch updates from the remote without merging them.                         |

### 5. **Collaborating on GitHub**
| Command                           | Description                                                                 |
|-----------------------------------|-----------------------------------------------------------------------------|
| `git remote add origin [url]`     | Link your local repository to a remote GitHub repository.                   |
| `git pull origin [branch]`        | Pull updates from the remote branch.                                        |
| `git push origin [branch]`        | Push your changes to the remote repository.                                 |
| `git fork`                        | Create a copy of someone else's repository to your GitHub account.          |
| `git pull request`                | Submit a request to merge your changes into the original repository.        |

---

## 🎯 Pro Tips
1. Use **`git stash`** to temporarily save your changes without committing them.
2. **`alias`** command can be used to create shortcuts for frequently used Linux or Git commands. Example: `alias gs='git status'`.

---
