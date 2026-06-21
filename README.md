# Git & GitHub Learning Journey

## Overview

This repository was created as part of a hands-on Git and GitHub learning exercise. The objective was to understand version control concepts, repository management, collaboration workflows, and GitHub project management features.

---

## Topics Learned

### 1. Git Setup and Configuration

* Installed Git
* Verified Git installation
* Connected Git with GitHub account

### 2. Repository Initialization

* Created a local repository using:

```bash
git init
```

* Understood the purpose of the `.git` folder

### 3. Tracking Changes

* Checked repository status using:

```bash
git status
```

* Added files to staging area using:

```bash
git add
```

### 4. Commits

* Created commits using:

```bash
git commit -m "message"
```

* Learned that commits act as snapshots of project history

### 5. Working with Remote Repositories

* Cloned repositories using:

```bash
git clone
```

* Connected local repository with GitHub

### 6. Fetch, Pull, and Push

* Downloaded remote updates using:

```bash
git fetch
```

* Integrated remote changes using:

```bash
git pull
```

* Uploaded local changes using:

```bash
git push
```

### 7. Understanding Git History

* Viewed commit history:

```bash
git log
git log --oneline
```

* Compared changes using:

```bash
git diff
```

### 8. README and .gitignore

Created:

* README.md
* .gitignore

Learned how to:

* Document projects
* Ignore unnecessary files
* Protect sensitive files

Examples:

```text
__pycache__/
*.pyc
.env
```

### 9. Branching Basics

Created and switched branches:

```bash
git branch feature-login
git switch feature-login
```

Learned:

* Parallel development
* Independent feature creation
* Safe experimentation

### 10. Feature Branch Workflow

Worked on a separate feature branch and pushed it to GitHub:

```bash
git add .
git commit -m "Add login feature"
git push origin feature-login
```

### 11. Pull Requests

Learned:

* Creating Pull Requests (PR)
* Comparing branches
* Requesting code integration
* Writing PR descriptions

### 12. Pull Request Review

Learned:

* Approve changes
* Comment on code
* Request modifications

### 13. Merge Conflicts

Experienced and resolved a real merge conflict.

Conflict markers:

```text
<<<<<<< HEAD
=======
>>>>>>>
```

Learned:

* Why conflicts occur
* Manual conflict resolution
* Completing merges

### 14. Rebase

Used:

```bash
git fetch
git rebase origin/main
```

Learned:

* Linear commit history
* Difference between merge and rebase

### 15. Issues, Labels, and Milestones

Created:

* Issues
* Labels
* Milestones

Learned:

* Project tracking
* Task management
* Sprint planning

### 16. Forking Workflow

Learned:

* Forking repositories
* Working with open-source projects
* Adding upstream remotes

Commands:

```bash
git remote add upstream <repository-url>
git pull upstream main
```

---

## Key Git Commands Learned

```bash
git init
git status
git add
git commit
git log
git diff
git clone
git fetch
git pull
git push
git branch
git switch
git merge
git rebase
git remote
```

---

## Skills Acquired

* Version Control
* Repository Management
* Branching Strategy
* Collaboration Workflow
* Pull Requests
* Code Reviews
* Conflict Resolution
* GitHub Project Management
* Open Source Contribution Workflow

---

## Learning Outcome

By completing these exercises, I gained practical experience with Git and GitHub, including repository management, collaboration workflows, branching strategies, pull requests, merge conflict resolution, rebasing, and project tracking. These skills form the foundation of modern software development and team collaboration.
