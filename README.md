# Git Exercises for Frontend Developers

## Setup

Clone this repository and you'll find three branches to work with:

- `ex1/start` - Exercise 1 starting point
- `ex2/start` - Exercise 2 starting point
- `ex3/start` - Exercise 3 starting point

For each exercise, checkout the corresponding branch and follow the instructions.

---

## Exercise 1: The Happy Path 🎯

**Goal:** Practice a standard feature branch workflow.

**Starting branch:** `ex1/start`

### Your Task

You're working on a new button component. Complete these steps:

1. Create a new branch called `feature/add-button` from `ex1/start`
2. Make changes to `stuff/button.js`:
   - Change the button text from "Click me" to "Submit"
   - Add a new className: `btn-primary`
3. Stage and commit your changes with message: "update button component"
4. Merge your feature branch into `main`

**Note:** Use `git switch` to change branches throughout these exercises.

**Success criteria:** Your changes are on `main`

## Tips & Hints 💡

**If you get stuck:**

- `git status` is your friend - run it often
- `git log --oneline --graph --all` shows you the full picture
- You can always reset to the starting branch: `git reset --hard ex1/start` (or ex2/start, ex3/start)

**Common commands you'll need:**

```bash
git branch <name>          # Create branch
git checkout <name>        # Switch branch
git add <file>             # Stage changes
git commit -m "message"    # Commit changes
git merge <branch>         # Merge branch
git stash                  # Save uncommitted work
git stash pop              # Retrieve stashed work
git reset                  # Undo commits
git log                    # View history
```

**Remember:** You're working in a practice repo. It's okay to make mistakes - that's how you learn!
