[Home Page](https://devaoc.github.io/reading-notes/)

# Reading Notes 03

## Read: Git Intro

[Link to Git Intro page](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)

There are special features of git that allow you to save all different versions of a project or file. It is called version control.

There are three different types of version control systems (VCS):

- Local Version Control
- Centralized Version Control
- Distributed Version Control

The specific version control system we are using in this class is GitHub. It is a Distributed Version Control System (DVCS). This means that it is a VCS that is not only on one server, and vulnerable to crashes if ever there is a problem, but stored on multiple (on the cloud).

### ACP

ACP stands for Add, Commit, Push. These are the three steps to adding something to a GitHub repository through the terminal.

##### Add

The commands and arguments to be used in the terminal are as follows:

- git add 'filename' (For single files)
- git add . (For multiple/all files)

##### Commit

The commands to commit the files that have been added to the index are:

- git commit -m "Small explanation of why" (This -m allows you to commit the files and write a message)
- git commit -a (Commit all files that have been previously added to the index, otherwise know as tracked)

##### Push

The command:

- git push origin main

Allows you to change the files that are viewed online to the commited versions. This brings the file to the repository origin in its main branch.
