
# Lab 4 Notes

## Question 1
`--global` means the Git configuration applies to my user account and is used by default across all repositories on my computer. If I leave it out, the setting applies only to the current repository.

## Question 2
The `.git` directory appeared in `ls -a` but not in normal `ls`. It contains Git's repository information, including history and other data Git uses to track the project.

## Question 3
Git is offering to track roughly 4 files and folders. The `.venv` directory looks like something I did not write because it contains the virtual environment and installed dependencies.

## Question 4
After creating `.gitignore`, the files inside `.venv/` disappeared from the untracked-files list. Git now ignores the patterns listed in `.gitignore`.

## Question 5
`.gitignore` should be committed because it is part of the project's configuration. Other people cloning the repository need it so Git ignores the same unnecessary files.

## Question 6
README.md moved from “Untracked files” to “Changes to be committed.” `git add` moved it from the working directory into the staging area.

## Question 7
Git created the commit and reported that 5 files changed. The commit saved the staged files as a permanent point in repository history.

## Question 8
The first seven characters of my commit hash are `51d8a47`. They are a short version of the commit's unique identifier.

## Question 9
The four steps are edit the files, check the changes with git status, stage the changes with git add, and commit them with git commit. This cycle is repeated whenever I make a logical change.

## Question 10
README.md has a special name because GitHub automatically recognizes it as the main documentation file for a repository. It is normally placed in the repository's top-level directory so visitors can immediately see the project's description and instructions

## Question 11
gh auth login authenticated my GitHub account in the terminal and configured GitHub CLI/Git to use that authentication. Because the credentials are stored through GitHub CLI's authentication mechanism, Git does not need to ask me for my GitHub password on every push.

## Question 12
The GitHub front page shows README.md rendered as formatted text. GitHub automatically displays a repository's README on its main page because it is intended to introduce and explain the project

## Question 13
No, pushing did not change my local Git history. git push copied my existing local commits to GitHub; it did not create a new local commit.

## Question 14
No, pushing did not change my local Git history. git push copied my existing local commits to GitHub; it did not create a new local commit.





