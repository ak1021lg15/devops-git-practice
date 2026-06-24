

# Git Commands

| Command | Usage | Example |
|----------|----------|----------|
| `git init` | initialize a repo inside directory | `git init` |
| `git clone <url>` | clone an existing repo | `git clone https://github.com/ak1021lg15/90DaysOfDevOps.git` |
| `git add file` | add untracked files | `git add demo.txt` |
| `git commit` | make a commit | `git commit -m "added demo.txt"` |
| `git reset file` | unstage a file | `git reset demo.txt` |
| `git status` | check if anything to commit/add | `git status` |
| `git log` | check commit history | `git log` |
| `git diff` | show unstaged changes | `git diff` |
| `git restore file` | discard local changes | `git restore demo.txt` |
| `git branch` | list all branches | `git branch` |
| `git branch` | list all branches | `git branch` |
| `git branch feature` | create a new branch | `git branch feature` |
| `git checkout feature` | switch branch | `git checkout feature` |
| `git checkout -b feature` | create and switch branch | `git checkout -b feature` |
| `git merge feature` | merge branch into current branch | `git merge feature` |


# Git Commands Cheat Sheet

## Repository Initialization

```bash
git init
```
Initialize a new Git repository.

```bash
git clone <repository-url>
```
Clone an existing repository.

---

## Check Status

```bash
git status
```
Show current repository status.

```bash
git log
```
Show commit history.

```bash
git log --oneline
```
Show commit history in one line.

```bash
git log --graph --oneline --all
```
