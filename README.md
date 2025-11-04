## Exercise 3: Merge Strategies Showdown ⚔️

**Goal:** Understand the difference between merge, squash, and rebase.

**Starting branch:** `ex3/start`

You'll do the same task three different ways to see how each strategy affects history.

### Part A: Standard Merge

1. Create branch `feature/merge-example` from `ex3/start`
2. Add a new file `merge-example.js` with some content
3. Make 2-3 small commits (edit the file between commits)
4. Switch to `main` and merge using: `git merge feature/merge-example`
5. Examine the history with `git log --oneline --graph`

**Note what you see:** All individual commits are preserved in history.

### Part B: Squash Merge

1. Reset `main` back to `ex3/start`: `git reset --hard ex3/start`
2. Create branch `feature/squash-example` from `ex3/start`
3. Add a new file `squash-example.js` with some content
4. Make 2-3 small commits (edit the file between commits)
5. Switch to `main` and merge using: `git merge --squash feature/squash-example`
6. Commit the staged changes with message: "feat: add squash example"
7. Examine the history with `git log --oneline --graph`

**Note what you see:** All commits are combined into a single commit on main.

### Part C: Rebase

1. Reset `main` back to `ex3/start`: `git reset --hard ex3/start`
2. Create branch `feature/rebase-example` from `ex3/start`
3. Add a new file `rebase-example.js` with some content
4. Make 2-3 small commits (edit the file between commits)
5. While on your feature branch, run: `git rebase main`
6. Switch to `main` and merge using: `git merge feature/rebase-example` (this will be a fast-forward)
7. Examine the history with `git log --oneline --graph`

**Note what you see:** Commits are replayed on top of main, creating a linear history.
