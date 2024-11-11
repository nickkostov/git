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

git log --graph --> show a textual graph of a project's commit history

git log --stat --> show statistics of the files with each commit

git log --prettry=fomat: format the output of a git log command to display specific fields check example

man git-log --> local documentation on using the 'git log' command


///
examples of "git log"

git log --since="4 days ago"

git log -S build

git stat

git log --pretty=format:"%h - %an - %ar - %s"om"

git config --global core.editor "/usr/bin/vim"  

cat ~/.gitconfig

git status --> shows what files are in the staging area

git status -a 

//