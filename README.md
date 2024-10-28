# Git Setup and Usage Guide

This guide provides essential Git commands for configuring Git, managing branches, and performing basic Git operations. Follow these steps to set up and manage your Git repository efficiently.

## Initial Configuration

Set up your Git user details (only required once per machine):

```bash
git config --global user.name "Nithish3115"
git config --global user.email "nithish031105@gmail.com"
```

**To verify your configuration**: 

```
git config --list   # Lists all Git configuration settings
```

 


**Basic Commands**:

| Command                             | Description                                       |
|-------------------------------------|---------------------------------------------------|
| `which git`                         | Show the location of Git in your system           |
| `git --version`                     | Display the installed Git version                 |
| `git log`                           | View the commit history (timeline)                |
| `git status`                        | Show the status of your working directory          |
| `git add .`                         | Stage all changes for commit                       |
| `git commit -m "message"`          | Commit staged changes with a message               |
| `git rm --cached <filename>`        | Remove a file from staging, even if already committed |
| `rm -rf .git`                       | Completely remove Git tracking from the directory  |
| `git reset`                          | Unstage all staged changes                        |

<br>

**Branch Management** :
| Command                             | Description                                      |
|-------------------------------------|--------------------------------------------------|
| `git branch`                        | Display the list of branches and the current branch |
| `git branch <branch_name>`         | Create a new branch                              |
| `git checkout <branch_name>`       | Switch to a specific branch                      |
| `git merge <branch_name>`          | Merge a specified branch into the current branch |

<br>

 Example Branching Workflow :

<br>
1.Create a New Branch:
```
git branch test1
```
2.Switch to the New Branch:

 ```
git checkout test1
```
3.Merge Branch: 
If you are on the main branch and want to merge test1:

 ```
git merge test1
```

Quickstart Workflow 
<br>

To initialize and commit changes quickly, follow these steps:

1. Initialize Git
```
git init
```

2. Stage All Changes
```
git add .
```

3. Check Status
```
git status
```

4. Commit Changes
 ```
git commit -m "test-1"
```







