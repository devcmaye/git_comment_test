# github_comment_test

A simple **Git & GitHub comment (command) demo project** for beginners.
This repository demonstrates **commonly used Git commands**, their **labels**, and **clear explanations**.

---

## 📌 Git / GitHub Useful Commands (With Labels)

### 🔹 Initialize Repository

```bash
git init
```

**Label:** Initialize Git
**Comment:** Create a new local Git repository in the current folder.

---

### 🔹 Check Repository Status

```bash
git status
```

**Label:** Check status
**Comment:** Show modified, staged, and untracked files.

---

### 🔹 Add All Files

```bash
git add .
```

**Label:** Add all files
**Comment:** Stage all new, modified, and deleted files for commit.

---

### 🔹 Add Specific File

```bash
git add README.md
```

**Label:** Add specific file
**Comment:** Stage only the `README.md` file.

---

### 🔹 Unstage a File (Keep Changes)

```bash
git restore --staged README.md
```

**Label:** Unstage file
**Comment:** Remove file from staging area without deleting changes.
⚠️ **Note:** This command works only after the first commit.
Before first commit, use:

```bash
git reset README.md
```

---

### 🔹 Commit Changes

```bash
git commit -m "feat: initialize project structure"
```

**Label:** Commit
**Comment:** Save staged changes with a clear commit message.

---

### 🔹 View Commit History

```bash
git log --oneline
```

**Label:** Commit history
**Comment:** Show commit history in short format.

---

### 🔹 Create New Branch

```bash
git branch feature/login
```

**Label:** Create branch
**Comment:** Create a new branch named `feature/login`.

---

### 🔹 Switch Branch

```bash
git checkout feature/login
```

or

```bash
git switch feature/login
```

**Label:** Switch branch
**Comment:** Move to another branch.

---

### 🔹 Create & Switch Branch (One Command)

```bash
git checkout -b feature/profile
```

**Label:** Create & switch branch
**Comment:** Create a new branch and switch to it immediately.

---

### 🔹 Add Remote Repository (GitHub)

```bash
git remote add origin https://github.com/username/repository.git
```

**Label:** Add remote
**Comment:** Connect local project to a GitHub repository.

---

### 🔹 Push Code to GitHub

```bash
git push -u origin main
```

**Label:** Push to GitHub
**Comment:** Upload commits to GitHub and set upstream branch.

---

### 🔹 Pull Latest Changes

```bash
git pull origin main
```

**Label:** Pull changes
**Comment:** Fetch and merge latest code from GitHub.

---

### 🔹 Clone Repository

```bash
git clone https://github.com/username/repository.git
```

**Label:** Clone repo
**Comment:** Download a GitHub repository to local machine.

---

### 🔹 Delete Local Branch

```bash
git branch -d feature/login
```

**Label:** Delete branch
**Comment:** Remove a local branch safely.

---

### 🔹 Ignore Files (.gitignore)

```gitignore
build/
.env
*.log
```

**Label:** Git ignore
**Comment:** Prevent files/folders from being tracked by Git.

---

## 🏷️ Common Commit Labels (Best Practice)

| Label       | Meaning                              |
| ----------- | ------------------------------------ |
| `feat:`     | New feature                          |
| `fix:`      | Bug fix                              |
| `refactor:` | Code improvement (no feature change) |
| `style:`    | UI / formatting changes              |
| `test:`     | Add or update tests                  |
| `docs:`     | Documentation only                   |
| `chore:`    | Build, config, or maintenance work   |

### ✅ Example Commit

```bash
git commit -m "fix: resolve login validation issue"
```

---

## ✅ Purpose of This Repository

* Learn basic Git commands
* Understand proper commit messages
* Practice GitHub workflow
* Use as a reference or teaching material

---

### ⭐ If this helps you, feel free to star the repository!
