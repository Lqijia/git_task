# Git Kata: Basic Ignore
We'll work a bit with the `.gitignore` file in this kata.
In this file you can specify both file extensions and folder structures that you do not want git to track.
You can still `git add` files and folder that maches in the `.gitignore` file.
 

## Setup:
Run `./setup.sh && cd exercise`

The setup script have made a file with the name `file1.txt` and made your own branch. 

## The task

1. Create a file with the name `.s`
1. What is the output of `git status`?
1. Create a `.gitignore` file in your working directory containing `*.s`
1. What is the output of `git status`?
1. Commit the `.gitignore` file
1. Commit `file1.txt`
1. Add `txt` files to `.gitignore` by adding a line in the file containing `*.txt`
1. What does `git status` tell us?
1. Change `file1.txt`
1. What does `git status` tell us? Why was the file tracked even though the `txt` extension is in the ignore file?
1. Make another textfile in the repository, what does `git status` look like now? Why is it not tracked?
1. Stage the removal of `file1.txt`
1. What does `git status` say?

## Useful commands
- `git rm`
- `git add`
- `git commit`
- `git commit -m`


## Aliases
You can set up aliases as such:
`git config --global alias.lol 'log --oneline --decorate --graph --all'`
This might be useful to you.