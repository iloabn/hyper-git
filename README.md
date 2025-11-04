## Exercise 2: Fixing a Messy Situation 🔧

**Goal:** Recover from common Git mistakes.

**Starting branch:** `ex2/start`

### The Situation

You're on the `ex2/start` branch. You've been working on `script.js` and made some commits, but things are messy:

- You accidentally committed sensitive data in `config/secrets.js`
- You need to get back to a clean state

### Your Task

1. Checkout `ex2/start` and examine the current state with `git status` and `git log`
1. Look at your commit history - find the commit that added `secrets.js`
1. Find a way to get rid of that commit
1. You want `ex2/start` to look the same, but without the commit that added `secrets.js`

**Success criteria:** You have two clean commits, no secrets file, and all your work is preserved.
