# Git Journey Diary

## Session 1
- Initialized first Git repo and created first commit
- Learned basics of `git add`, `git commit`, and `git push`
- Added `hello.txt` as the first tracked file

## Session 2
- Explored branching (`feature-1`, `feature-2`, `experiment`)
- Practiced editing files in different branches
- Understood merge basics and conflict resolution
- Saw how commits diverge across branches

## Session 3
- Learned to interpret `git log --graph --decorate --oneline --all`
- Understood meaning of commits like “Add line 1”
- Saw how branches diverge and merge in the commit tree
- Sketched simplified diagram of repo’s history
- Set up Git Journey Diary to track progress session by session
### Session 5 Summary – Undoing Mistakes and Repo Insights

- Practiced **undoing mistakes** using Git commands:
  - `git restore` – discard uncommitted changes in files.
  - `git restore --staged` – unstage changes while keeping edits in the working directory.
  - `git reset --soft` – undo the last commit while keeping changes staged.
- Clarified that **“Git Journey Diary”** exists in commit messages, while the actual file is `git-diary.md`.
- Learned why the **git-diary/ folder** may remain in the working directory (Git does not track empty directories).
- Encountered and resolved a **common case-sensitivity issue** (`Git` vs `git`).
- Prepared a clear understanding of how to **keep work safe while experimenting** with undo operations.
