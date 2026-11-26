# Session 1 Reflection

**Name:** Irteira Firza Binti Rozman
**Student ID:** 99173
**Method:** I did all local work with the Git command line (Git Bash on Windows 11).

## Q1. Why is a commit history useful when maintaining software?

A commit history shows every change, who made it and when. This helps when a bug appears. I can look at the history and find the commit that caused it. For example, `git log --oneline` shows that I added `.gitignore` in its own commit. If that file caused a problem, I would know exactly when it was added and could undo only that change.

## Q2. What is the difference between Git and GitHub?

Git is a program on my computer. It saves snapshots of my files. GitHub is a website that stores Git repositories online. I created `scm-lab-evidence` with Git on my computer first, and GitHub did not know about it until I ran `git push`. My exercise repository was different. It was made on GitHub and used GitHub features like pull requests and the Actions bot.

## Q3. What risk does a branch and pull request reduce?

In the GitHub Skills exercise, I worked on the branch `my-first-branch` and merged it with pull request #1. My change stayed away from `main` until I merged it. This lowers the risk of breaking the main working version. A pull request also gives others a chance to review the change first. Mistakes can be found before they reach `main`.

## Q4. Which commands changed only my computer, and which changed GitHub?

Most commands changed only my computer. These were `git config`, `git init`, `git add`, `git commit`, `git diff`, `git status`, `git switch`, `git merge`, `git branch -d`, `git restore` and `git remote add`. Only `git push` changed GitHub, because it uploaded my commits. `git clone` and `git pull` downloaded from GitHub but did not change it.

## Concept table

| Term                 | My definition                                                                                                                                       |
| -------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| Repository           | A project folder along with the full history of its changes.                                                                                        |
| Working tree         | The files I can see and edit on my computer.                                                                                                        |
| Staging area (index) | The list of changes I choose to put in the next commit.                                                                                             |
| Commit               | A saved snapshot of the files, with a message, author and date.                                                                                     |
| Branch               | A pointer to a line of commits, so I can work on something separately.                                                                              |
| Merge                | Combining the work from one branch into another.                                                                                                    |
| Remote               | A copy of the repository on another server, such as `origin` on GitHub.                                                                             |
| Push / Pull / Clone  | Push uploads my commits. Pull downloads new commits and adds them to my branch. Clone copies a remote repository to my computer for the first time. |
