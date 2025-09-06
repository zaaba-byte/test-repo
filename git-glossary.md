# Git Glossary

A running collection of important Git terms and their meanings.  
This file will grow as I learn and practice Git.

---

## HEAD
- A reference that points to the current commit in the checked-out branch.  
- Think of it as “where you are” in the repo’s history.  
- Usually points to the latest commit of the current branch.

---

## Branch
- A movable pointer to a commit.  
- Represents an independent line of development.  
- The default branch is often `main`.  
- Branches allow you to work on features or fixes without disturbing the main code.

---

## Commit
- A snapshot of the repository at a point in time.  
- Contains changes, a unique ID (SHA hash), author info, and a message.  
- Commits form the history of the project.

---

## Remote
- A version of your repository that is hosted elsewhere (e.g., GitHub).  
- Acts like a shared reference so others can collaborate.  
- Common remote name: `origin`.  
- You `push` to send changes to it and `pull`/`fetch` to bring changes from it.

---

*(More terms to be added as I continue learning Git.)*
---

## Git History (Visual)

### Example: `git log --graph --oneline --decorate`

---

## Git History (Visual)

### Example: `git log --graph --oneline --decorate`


- `*` → shows a commit node  
- `HEAD -> main` → current position (HEAD is pointing at `main`)  
- `origin/main` → remote branch pointer  
- The commit hash (e.g., `f3c2a11`) is the unique ID  

---

## Detached HEAD
- When HEAD points directly to a commit instead of a branch.  
- Happens when you check out a commit hash or a tag directly.  
- You can look around history but new commits won’t belong to a branch unless you create one.
A---B---C main
         \
          D---E feature
---

## Visual Git History

### git log --graph --oneline --decorate

This command shows a compact visual representation of the commit history.

Example output:


### Branch Diagram Example

## Git Glossary

**Graph (`--graph`)** → ASCII tree of commits and branches.  
**Decorate (`--decorate`)** → Show branch names, HEAD, tags on commits.  
**Oneline (`--oneline`)** → Compact one-line-per-commit view.  
**All (`--all`)** → Include history from all branches, not just current.  
