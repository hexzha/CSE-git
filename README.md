# Git — CSE Club @ Iowa State University

Introduction to Git

## Motivation

Git is a version control system that was created to help developers
track changes in code and manage collaborative project.
Just as you might write several drafts of an English paper, a
programmer might write several drafts of a program. Git keeps
track of which draft is which, and also makes it easy to share the
files with others.

Git helps use: 
- Compare versions to locate changes or bugs
- rollback to previous versions of files as necessary
- store multiple versions of a file
- merge versions and resolve conflicts that arise from collaboration

## Create a Github Account

https://github.com/

## Installation

https://git-scm.com/download

## Git Config

$ git config --global user.name "YOUR NAME"

$ git config --global user.email \<YOUR EMAIL\>

$ git config --list 

## Git Commands

- $ git init

  Initializes a new Git repository. Current folder is just a normal folder otherwise


- $ git clone \<repo url\>

  Create a copy of an online repo from Github. Don't need to use init if cloning a repo


- $ git status

  See the status of the current repo


- $ git add \<file name\>

  Have Git track a file and add <file name> to staging


- $ git commit -m "Concise message for changes made"

  Create a snapshot for files Git is tracking


## Putting Work onto GitHub

- $ git remote add origin \<GitHub url\>

  Have Git on local machine track a remote repo


- $ git push -u origin master

  Adding local changes to remote repo


- $ git remote -v
  
  Viewing remote repos Git is tracking from
  

## Getting Changes from GitHub

- $ git pull origin master

  Take the changes from GitHub repo to local repo
  
## More Commands
[git cheet sheet](https://education.github.com/git-cheat-sheet-education.pdf)
  
