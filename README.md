# 🗂️ Git Version Control 

> Learn Git version control with commands, examples, and learning resources.

---

## 🧠 What is Version Control?

Version control helps track changes in files, collaborate with others, and revert to earlier versions.  
Git is the most popular version control tool today.

🔗 [Git SCM - About Version Control](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control)

---

## 🐙 What is Git?

Git is a **distributed** version control system for source code management.

- Distributed → Every developer has the full repo
- Fast → Operations are local
- Secure → Uses SHA-1 to track changes

🔗 [Official Git Website](https://git-scm.com)

---

## 🧱 Why Use Git?

- 🔄 Track project history
- 👨‍💻 Collaborate with teams
- ⏪ Undo mistakes
- 🌳 Branch for parallel development
- ☁️ Work with GitHub, GitLab, etc.

---

## 🛠️ Installation & Configuration

### ✅ Install Git  
🔗 [Download Git](https://git-scm.com/downloads)

```bash
git --version
```
### 🔧 Configure Git (One-Time)
```
git config --global user.name "Your Name"
git config --global user.email "you@example.com"

```
### 📁 Create or Clone a Repository
Initialize a local repo
```
git init
```
Clone a remote repo
```
git clone https://github.com/user/repo.git
```
Check Status
```
git status
```
### 🔄 Track and Commit Changes
Stage changes
```
git add <file>     # Stage one file
git add .          # Stage all files
```
Commit staged files
```
git commit -m "Your commit message"
```
Check status
```
git status
```
View changes before committing
```
git diff
```
### 🔁 Work with Remote Repositories
Add remote origin
```
git remote add origin https://github.com/user/repo.git

```
Push commits to GitHub
```
git push -u origin main
```
Pull latest changes
```
git pull origin main
```
### 🌿 Branching in Git
Branches allow working on features independently.

Create a branch
```
git branch feature-name

```
Switch to branch
```
git checkout feature-name
```
OR create and switch:
```
git checkout -b feature-name
```
List branches
```
git branch
```
Merge a branch
```
git checkout main
git merge feature-name
```
Delete a branch
```
git branch -d feature-name
```
### ⚠️ Merge Conflicts
Git shows conflict markers in the file

Manually fix the file

Stage and commit:
```
git add <file>
git commit
```
### 🧹 Undoing Changes
Unstage a file
```
git reset HEAD <file>
```
Undo last commit (keep changes)
```
git reset --soft HEAD~1
```
Discard local changes
```
git checkout -- <file>
```
## 📄 Common Git Commands Summary

| Command                       | Description                         |
|------------------------------|-------------------------------------|
| `git init`                   | Initialize local repo               |
| `git clone <url>`            | Clone remote repo                   |
| `git status`                 | Show file states                    |
| `git add .`                  | Stage all changes                   |
| `git commit -m "msg"`        | Save changes to local repo          |
| `git push`                   | Upload to remote repo               |
| `git pull`                   | Fetch & merge remote changes        |
| `git branch`                 | List branches                       |
| `git checkout -b <name>`     | Create and switch to new branch     |
| `git merge <branch>`         | Merge branch into current branch    |
| `git log`                    | Show commit history                 |

This is a complete guide to learn about Git version contols 
