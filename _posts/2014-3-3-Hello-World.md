---
layout: post
title: "Understanding Version Control with Git"
---

Git is a distributed version control system created by Linus Torvalds in 2005. It allows you to track project history, collaborate effectively in teams, and manage multiple versions of the same source code.

## Why use Git?

- **Complete history** : Every change is recorded with its author, date, and a descriptive message.
- **Parallel work** : Branches allow you to develop multiple features simultaneously without conflicts.
- **Simplified collaboration** : Multiple developers can work on the same project without overwriting each other's work.
- **Backup and restore** : It's easy to revert to an earlier version of the project if something goes wrong.

## Essential commands

```bash
# Initialize a Git repository
git init

# Clone an existing repository
git clone https://github.com/user/project.git

# Check file status
git status

# Add a file to the staging area
git add filename

# Commit changes
git commit -m "Message describing the changes"

# Push changes to the remote repository
git push

# Fetch the latest changes
git pull