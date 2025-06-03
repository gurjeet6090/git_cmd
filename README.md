# 📘 Git Commands Cheat Sheet

A complete reference of commonly used Git commands for daily development.

---

## ✅ Setup & Configuration
```bash
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
git config --list


## 📁 Repository Management
```bash
git init
git clone <repo-url>
git remote add origin <repo-url>
git remote -v
git remote remove origin

## 🔄 Status & Changes
```bash
git status
git diff
git diff --staged

## ➕ Add & Commit
```bash
git add <file>
git add .
git commit -m "Your message"

## 🔀 Branching
```bash
git branch
git branch <name>
git checkout <branch>
git checkout -b <branch>
git branch -d <branch>
git branch -D <branch>

## ⬆️⬇️ Push & Pull
```bash
git push origin <branch>
git push -u origin <branch>
git pull origin <branch>
git fetch

##🔁 Merge & Rebase
```bash
git push origin <branch>
git push -u origin <branch>
git pull origin <branch>
git fetch

🧼 Undo / Reset
```bash
git reset --soft HEAD~1
git reset --hard HEAD~1
git checkout -- <file>

🕓 Logs & History
```bash
git log
git log --oneline
git log --oneline --graph --all

🧪 Stash
```bash
git stash
git stash apply
git stash list
git stash drop

🗑️ Remove Files
```bash
git rm <file>
git rm --cached <file>

🔍 Tagging
```bash
git tag
git tag <tag-name>
git push origin <tag-name>

🛠️ Submodules
```bash
git submodule add <repo-url> path/
git submodule update --init

🌍 Change Remote URL
```bash
git remote set-url origin <new-url>
