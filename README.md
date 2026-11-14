# Git Workflow Assignment

Kushal S, Roll No. 2024eb02539

A small two-page website (`index.html`, `about.html`) used to practise a full Git workflow,
from a local repository through to this public GitHub repo.

## Commit history

| # | What happened | Git operation |
|---|---------------|---------------|
| 1 | Initial commit of both HTML pages | `git commit` |
| 2 | Last-updated note added to `index.html` | `git commit` |
| 3 | "Our Team" section added to `about.html` on the `feature` branch | `git branch`, `git switch` |
| 4 | `feature` merged back into `main` | `git merge --no-ff` |
| 5 | `.gitignore` added for `*.log` and `temp/` | `git commit` |
| 6 | Contact link added, then undone | `git revert` |

An extra commit was also undone locally with `git reset --hard HEAD~1` before anything
was pushed, so it does not appear here.

## Files

- `index.html`, `about.html`: the website pages
- `.gitignore`: ignore rules
- `git_commands.txt`: every command used, with a short explanation of each
