# Useful Git Commands:

### Check Git Version:

```bash
git --version
```

### Get Path of Git Bin:

```bash
whcih git
```
### How to create a Git repository (repo)-command:

```bash
git init /path/to/directory (repository folder name here)

git init --bare /path/to/directory

ls -a (repository folder name here)
```

### Git Configurations for User and Email:

```bash
git config --global user.name "Name OF Person"

git config --global user.email "email@email.c
```
### Shows information for a specific branch:

```bash
git status -b
```

### Short version of git status:

```bash
git status -s 
```

### "Verbose" version of git status == `git status`

```bash
git status -v
```

### Manual Page of Git Status:

```bash
man git-status
```

### Add file to the index file (stages files)
```bash
git add
```

### Remove file from a project:
```bash
git rm
```

### Get repository History:
```bash
git log
```

### Get historical statistics:
```bash
git log --graph 
```
### Get Statistics of the files with each commit
```bash
git log --stat
```
### Get manual page of Git Log
```bash
man git-log
```

### Get Git Log for the last period
```bash
git log --since="4 days ago"
```
### Look for differences that change the number of occurrences of the specified string (i.e. addition/deletion) in a file. Intended for the scripter’s use.
```bash
git log -S build
```
### Gets changes and shows you whne was the last change applied
```bash
git log --pretty=format:"%h - %an - %ar - %s"'om'
```
### Select Core Editor (My preferences are VSC and VIM)
```bash
git config --global core.editor "/usr/bin/vim"  
```
### Location of .gitconfig in UNIX/Linux based systems:

```bash
cat ~/.gitconfig
```