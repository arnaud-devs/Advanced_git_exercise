# Getting Started
```bash
git add test1md
git commit -m "chore: Create initial file"
git add test2.md 
git commit -m "chore: Create another file"
git add test3.md
git commit -m "chore: Create third and fourth files"
```

# challenges
## Part 1: Refining Git History (10 Challenges)
### 1. Missing File fix:
```bash
git status
git log
git add test4.md
git commit --amend --no-edit
```
### 2. Editing Commit history:
```bash
git rebase -i HEAD~2
```
### 3. Keeping History Tidy - Squashing Commits:
```bash
git rebase -i HEAD~2
```
### 4. Splitting a Commit:
```bash
git rebase -i --root
git reset HEAD^
git add test3.md
git commit -m "chore: Create third file"
git add test4.md
git commit -m "chore: Create fourth file"
git rebase --continue
git log --oneline
```
### 5. Advanced Squashing:
```bash
git rebase -i HEAD~2
```
### 6. Dropping a Commit:
```bash
git add unwanted.txt
git commit -m "Unwanted commit"
git rebase -i HEAD~2
```



