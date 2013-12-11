git-introduccion-labplc
=======================

Una introduccion a Git y Github para LabPLC


## Most useful commands

```bash
git status # shows status of current files
git log # show history of commits
git remote -v # show all remote repos
git diff # show differences (those that have NOT been committed)
git branch # show all branches (your CURRENT branch will have a * next to it)
```

## How to set up a new Git project

```bash
mkdir project-name
git init
touch algo
git commit -m "New file (or other git message)"
```

## Creating a repo on GitHub

- Go to www.github.com
- Click "New repository"
- Give a name, and "Create repository"
- On your local computer, add a git remote for GitHub (we call it "origin"):

`git remote add origin git@github.com:daguar/git-introduccion-labplc.git`
- Push to GitHub:

`git push origin master`


## Gitignore

`.gitignore` is a file you can add to tell git to ignore files in your working directory

For a list of useful .gitignore files GitHub: https://github.com/github/gitignore
