# Git Homework — 11th Grade

Complete each exercise in order. Each one builds on the previous.

---

## Exercise 1 — Create Your First Repository

1. Create a new folder on your computer called `my-first-repo`.
2. Open the terminal, navigate into that folder.
3. Run `git init` to turn it into a Git repository.
4. Create a file called `info.txt` and write your name and class inside it.
5. Run `git add info.txt` to stage it.
6. Run `git commit -m "add info file"` to save your first snapshot.

**What to submit:** A screenshot of your terminal showing the commit message confirmation.

---

## Exercise 2 — Make More Commits

1. Open `info.txt` and add a new line: your favorite subject.
2. Stage and commit with the message `"add favorite subject"`.
3. Add one more line: your hobby.
4. Stage and commit with the message `"add hobby"`.
5. Run `git log` to see all 3 commits in your history.

**What to submit:** A screenshot of `git log` output showing all 3 commits.

---

## Exercise 3 — Working with Branches

1. Inside `my-first-repo`, create a new branch called `new-feature`.
2. Use `git checkout` to switch to that branch.
3. Create a new file called `feature.txt` and write anything inside it.
4. Stage and commit with the message `"add feature file"`.
5. Use `git checkout` to switch back to `main` (or `master`).
6. Notice that `feature.txt` is no longer visible — it only exists on the `new-feature` branch.

**What to submit:** Screenshots showing: the new branch, the commit on it, and switching back to main.

---

## Exercise 4 — Branches for Different Ideas

1. From the `main` branch, create two branches: `idea-1` and `idea-2`.
2. Switch to `idea-1` and create a file `idea1.txt` with a short description of any app idea you have. Commit it.
3. Switch to `idea-2` and create a file `idea2.txt` with a different app idea. Commit it.
4. Switch back to `main` — neither file should be visible there.
5. Run `git branch` to list all your branches.

**What to submit:** A screenshot of `git branch` showing all three branches.

---

## Grading

| Exercise | Points |
|----------|--------|
| Exercise 1 | 20 |
| Exercise 2 | 25 |
| Exercise 3 | 25 |
| Exercise 4 | 30 |
| **Total** | **100** |
