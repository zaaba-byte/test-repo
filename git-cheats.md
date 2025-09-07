# 🌱 Solstice’s Git Cheat Sheet (Growing Bundle)

### 🔹 Committing
- `git commit -m "message"` → **m = message** (add your note right here).  

### 🔹 Viewing History
- `git log -n 3` → **n = number** (show the last 3 commits).  
- `git log --oneline` → short + sweet history view.  

### 🔹 Staging & Unstaging
- `git add file.txt` → stage changes.  
- `git restore --staged file.txt` → unstage, but keep edits.  

### 🔹 Undoing Changes
- `git restore file.txt` → throw away uncommitted changes.  
- `git reset --soft HEAD~1` → undo last commit, keep changes staged.  
- (More: `--mixed`, `--hard`, `git revert` → coming soon).  

---

✅ One by one makes a bundle — this sheet will grow with each session.
