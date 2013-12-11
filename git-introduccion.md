# Git & GitHub Overview

```bash
git log # show history
git status # shows status of current files
git remote -v # show all the remote repos
git diff # show differences (not committed)
```
## Gitignore

`.gitignore` is a file you can add to tell git to ignore files in your working directory

List of helpful .gitignore files GitHub: https://github.com/github/gitignore

## Setup for new git project

```bash
mkdir project-name
git init
touch algo
git commit -m "New file (or other git message)"
```

## GitHub steps

- Click "New repository"
- Give a name, and "Create repository"
- Add a git remote:

`git remote add origin git@github.com:daguar/git-introduccion-labplc.git`
- Push to GitHub:

`git push origin master`
