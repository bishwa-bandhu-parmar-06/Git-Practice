# My Git Practice

This README contains all the important Git and GitHub commands with simple explanations for daily use. Perfect for beginners and experienced developers alike! 🚀

---

## 🔧 Initial Setup (Run Once)

```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```
👉 Sets your Git identity globally so every repo knows who you are.

---

## 📂 Create a New Local Repository

```bash
git init
```
👉 Initializes a new Git repository in your project folder.

---

## 📝 Add & Commit Changes

```bash
git add .
```
👉 Stages all changes for the next commit.

```bash
git commit -m "Your commit message"
```
👉 Commits the staged files with a message.

---

## 📌 Check Current Status & History

```bash
git status
```
👉 Shows which files are staged, modified, or untracked.

```bash
git log
```
👉 Displays the history of commits.

---

## 🌐 Connect to Remote Repository (GitHub)

```bash
git remote add origin <repo-url>
```
👉 Links your local repository to a GitHub repository.

```bash
git push -u origin main
```
👉 Pushes your local main branch to GitHub for the first time.

```bash
git push
```
👉 Pushes new commits to GitHub after the initial push.

---

## ⬇️ Pull Latest Changes from GitHub

```bash
git pull
```
👉 Fetches and merges changes from the remote repository to your local.

---

## 🌿 Work with Branches

```bash
git checkout -b new-branch-name
```
👉 Creates and switches to a new branch.

```bash
git switch main
```
👉 Switches back to the main branch.

```bash
git merge new-branch-name
```
👉 Merges the specified branch into your current branch (usually `main`).

---

## 🛠️ Undo Changes (Rescue Commands)

```bash
git restore <filename>
```
👉 Reverts a file back to its last committed state.

```bash
git reset <filename>
```
👉 Unstages a file (removes it from staging).

```bash
git reset --hard
```
👉 Discards all local changes permanently (⚠️ irreversible).

```bash
git diff
```
👉 Shows the changes that are not yet staged or committed.

---

## 💡 Recommended Practice Flow

1. Create a GitHub repo called `git-practice`
2. Clone it or run `git init` locally
3. Add a file (e.g., `readme.md`)
4. Use `git add .` → `git commit -m "Initial commit"`
5. Link to GitHub and push
6. Try branching → editing → merging

---

## 📘 Tips

- Use `.gitignore` to avoid tracking unnecessary files
- Always check `git status` before pushing
- Use branches for new features or experiments

---

Happy Coding! 💻🎉
