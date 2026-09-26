# 🔧 Git Commands Reference

A practical reference for commonly used Git commands and GitHub workflows.

---

## ⚙️ Git Setup

### Check Git Version

```bash
git --version
```

### Configure Username

```bash
git config --global user.name "Your Name"
```

### Configure Email

```bash
git config --global user.email "your@email.com"
```

### View Git Configuration

```bash
git config --list
```

---

## 🚀 Create a Repository

### Initialize Git

```bash
git init
```

### Check Repository Status

```bash
git status
```

### Add All Files

```bash
git add .
```

### Commit Changes

```bash
git commit -m "Initial commit"
```

---

## 🌐 GitHub Remote

### Add Remote Repository

```bash
git remote add origin https://github.com/USERNAME/REPOSITORY.git
```

### Check Remote

```bash
git remote -v
```

### Change Remote URL

```bash
git remote set-url origin https://github.com/USERNAME/REPOSITORY.git
```

---

## 📤 Push to GitHub

### Push Main Branch

```bash
git push -u origin main
```

### Push Future Changes

```bash
git push
```

---

## 📥 Download Repository

### Clone a Repository

```bash
git clone https://github.com/USERNAME/REPOSITORY.git
```

### Clone into a Specific Folder

```bash
git clone https://github.com/USERNAME/REPOSITORY.git folder-name
```

---

## 🌿 Branches

### Show Branches

```bash
git branch
```

### Create a Branch

```bash
git branch feature-name
```

### Switch Branch

```bash
git switch feature-name
```

### Create and Switch

```bash
git switch -c feature-name
```

### Delete a Branch

```bash
git branch -d feature-name
```

---

## 🔄 Updating Your Repository

### Download Remote Changes

```bash
git fetch
```

### Pull Changes

```bash
git pull
```

### Pull from Main Branch

```bash
git pull origin main
```

---

## 📝 Commit Workflow

A common workflow for updating a project:

```bash
git status
git add .
git commit -m "Update project"
git push
```

---

## ↩️ Undo Changes

### Unstage a File

```bash
git restore --staged file.txt
```

### Discard Changes in a File

```bash
git restore file.txt
```

### View Commit History

```bash
git log
```

### Short Commit History

```bash
git log --oneline
```

---

## 🔍 Compare Changes

### Show Uncommitted Changes

```bash
git diff
```

### Show Staged Changes

```bash
git diff --staged
```

---

## 🏷️ Tags

### Create a Tag

```bash
git tag v1.0.0
```

### Show Tags

```bash
git tag
```

### Push a Tag

```bash
git push origin v1.0.0
```

---

## 🧹 Useful Commands

### Show Remote URL

```bash
git remote -v
```

### Check Current Branch

```bash
git branch --show-current
```

### Show Commit History

```bash
git log --oneline --graph --decorate
```

---

## 📌 Common GitHub Workflow

For a new project:

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/USERNAME/REPOSITORY.git
git push -u origin main
```

For an existing project:

```bash
git add .
git commit -m "Update project"
git push
```

---

## ⚠️ Important Notes

Never commit passwords, API keys, database credentials, private keys, or other sensitive information.

Use a `.gitignore` file to prevent sensitive or unnecessary files from being committed.

Example:

```text
node_modules/
.env
dist/
__pycache__/
*.log
```

Always check `git status` before committing changes.
