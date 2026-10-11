# Proof of Work

## 1. Git Commit History

The following output records the commits created during the practical activity.

- 10fb2b2 (HEAD -> main, origin/main) Merge pull request #1 from M-Shameel-375/development
- e844428 (origin/development, development) fix: resolved merge conflict
- ad67605 (origin/staging, staging) fix: staging label
- 5379de9 feat: updated script with staging env
- e2926fd feat: initial commit with deploy script

## 2. Reflection Questions

### Q1. Difference between Git and GitHub

Git is a version control system that tracks changes to files and stores project history. GitHub is a cloud-based platform where Git repositories can be hosted and shared. Git supports commits and branches, while GitHub provides collaboration tools such as Pull Requests and code reviews.

### Q2. Explain the three stages of Git

The Working Directory contains files that are being edited. The Staging Area holds the changes selected for the next commit using `git add`. The Local Repository stores committed changes and the project's version history. Together, these stages help organize and record modifications to a project.

### Q3. Difference between git stash pop and git stash apply

Both commands restore changes that were previously saved using Git stash. The `git stash pop` command normally removes the restored entry from the stash list after applying it successfully. In contrast, `git stash apply` leaves the saved entry in the list. This allows the changes to be applied again if required.

### Q4. Difference between git fetch and git pull

The `git fetch` command downloads information about updates from a remote repository without integrating them into the current branch. The `git pull` command retrieves remote changes and integrates them into the current branch, usually through a merge or rebase. Fetch is useful for inspecting updates first, while pull is used to bring the local branch up to date.
