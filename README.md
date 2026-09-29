# ProjectAI
## Git Basics

## What is a Repository?

A **repository** (repo) is a folder where Git tracks all changes to your files. It stores the full history of your project — every version, every change, and who made it.

---

## Local Repository

A **local repository** lives on your own computer. When you run `git init`, Git creates a hidden `.git` folder inside your project directory. This is your local repo — it works completely offline.

---

## Remote Repository

A **remote repository** lives on a server (like GitHub, GitLab, or Bitbucket). It allows multiple people to collaborate on the same project. You push your local changes to the remote so others can see them, and pull their changes down to your machine.

---

## Basic Git Commands

### `git init`
Initializes a new Git repository in the current folder.
```bash
git init
```
This creates the hidden `.git` folder and starts tracking your project.

---

### `git add`
Stages files — tells Git which changes you want to include in the next commit.
```bash
git add filename.txt       # stage a specific file
git add .                  # stage all changed files
```

---

### `git commit`
Saves a snapshot of your staged changes with a message describing what you did.
```bash
git commit -m "your message here"
```

---

### `git branch`
Lists, creates, or deletes branches. A branch is an independent line of development.
```bash
git branch                 # list all branches
git branch feature-login   # create a new branch called feature-login
git branch -d feature-login  # delete a branch
```

---

### `git checkout`
Switches to a different branch, or restores a file to a previous state.
```bash
git checkout main              # switch to the main branch
git checkout feature-login     # switch to the feature-login branch
git checkout -b new-branch     # create and switch to a new branch in one step
```

---

## Typical Workflow

```bash
git init                        # 1. initialize a repo
git add .                       # 2. stage your changes
git commit -m "first commit"    # 3. commit the snapshot
git branch feature-x            # 4. create a new branch
git checkout feature-x          # 5. switch to it and start working
```
