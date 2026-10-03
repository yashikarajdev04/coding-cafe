
# Lab 4 Notes

## Question 1
`--global` means the Git configuration applies to my user account and is used by default across all repositories on my computer. If I leave it out, the setting applies only to the current repository.

## Question 2
The `.git` directory appeared in `ls -a` but not in normal `ls`. It contains Git's repository information, including history and other data Git uses to track the project.

## Question 3
Git is offering to track roughly ___ files and folders. The `.venv` directory looks like something I did not write because it contains the virtual environment and installed dependencies.

## Question 4
After creating `.gitignore`, the files inside `.venv/` disappeared from the untracked-files list. Git now ignores the patterns listed in `.gitignore`.

## Question 5
`.gitignore` should be committed because it is part of the project's configuration. Other people cloning the repository need it so Git ignores the same unnecessary files.

## Question 6
README.md moved from “Untracked files” to “Changes to be committed.” `git add` moved it from the working directory into the staging area.

## Question 7
Git created the commit and reported that ___ files changed. The commit saved the staged files as a permanent point in repository history.

## Question 8
The first seven characters of my commit hash are `_______`. They are a short version of the commit's unique identifier.




