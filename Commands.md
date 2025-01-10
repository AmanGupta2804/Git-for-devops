# Git Commands Organized by Topics

## Repository Setup
```bash
mkdir git-for-devops
cd git-for-devops/
pwd
git init
```

## Viewing Files and Directories
```bash
ls -l
ls
ls -a
```

## Creating Files
```bash
touch nibba.txt
touch nibbi.txt
touch nibbu.txt
```

## Checking Repository Status
```bash
git status
```

## Adding Files to Staging
```bash
git add nibba.txt
git add nibbi.txt
git add nibbu.txt
git add .
```

## Removing Files from Staging
```bash
git rm --cached nibba.txt
```

## Committing Changes
```bash
git commit -m "adding files"
git commit -m "added nibbu"
```

## Configuring User Details
```bash
git config --global user.email "Aman gupta"
git config --global user.name "aman2828g@gmail.com"
```

## Viewing Commit History
```bash
git log
git log --oneline
```

## Branch Management
```bash
git branch
git branch -b dev
git checkout -b dev
```


## Miscellaneous
```bash
history
