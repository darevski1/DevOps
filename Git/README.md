# Git

## SETUP

Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency

# Git

## SETUP

Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency

### Configuring user information used across all local repositories

##### Example
commit 5254901063c7e7852cf788357cef
Author: Darko  <example@example.com>
Date:   Sun Feb 19 01:19:41 2023 +0100

    readme file added in git

### Basic git commands
$ **git config --global user.name** youname
Setup an username

---

$ **git config --global user.email** example@example.com
Setup an email address that will be associated with each history marker

---


$ **git status** 
Gives information on the current content status of a git repository and its contents
---
$ **git init**
Create new repository, Before we can do anything git-related, we must initalize a repo first.

Example - create new folder **myfirstrepo** open the folder via cmd and type **git init**

    mkdir myfirstrepo // create folder
    cd myfirstrepo // accees the foolder
    git init // initalize a repo
Output:
Initialized empty Git repository in **C:/path/to/the/reposity/myfirstrepo/.git/**
___
$ **git log** 
Shows a default output for quickly reviewing the commit history
___

