# GitHub Task Project

## Project Overview
This project demonstrates basic Git and GitHub operations using Shell scripting files in a Linux/WSL environment.

The project includes:
- Git repository initialization
- Connecting local repository to GitHub
- Pushing files to GitHub
- Branch creation
- Merge operation
- Rebase operation
- Stash operation

---

## Technologies Used

- Git Bash
- GitHub
- Shell Scripting
- Visual Studio Code

---

## Project Structure

```bash
backup.sh
deploy.sh
monitor.sh
README.md
```

---

## Shell Scripts

### backup.sh
Used for backup-related commands.

### deploy.sh
Used for deployment-related commands.

### monitor.sh
Used for monitoring-related commands.

---

## Git Commands Used

### Initialize Repository

```bash
git init
```

### Add Files

```bash
git add .
```

### Commit Changes

```bash
git commit -m "Initial commit"
```

### Connect Remote Repository

```bash
git remote add origin <repo-url>
```

### Push Code

```bash
git push -u origin main
```

---

## Branch Operations

### Create Branch

```bash
git checkout -b feature-branch
```

### Merge Branch

```bash
git merge feature-branch
```

---

## Rebase Operations

```bash
git rebase main
```

---

## Stash Operations

### Save Temporary Changes

```bash
git stash
```

### Restore Changes

```bash
git stash pop
```

---

## Outcome

Successfully completed:
- GitHub repository setup
- Local to remote repository connection
- Merge operation
- Rebase operation
- Stash operation

---

## Author

MITHUN GK