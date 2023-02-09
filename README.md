# File states

## Modified
File modified but not committed

## Staged
File modified and will be in the commit snapshot

## Committed
File is stored in the local database

# Project sections
<img src="screenshots/project-sections.png" width="350" height="200">

## Working tree
A single checkout of one version of the project.
These files are pulled out of the compressed database in the Git directory and placed on disk for you to use or modify.

## Staging area
File, generally contained in your Git directory, that stores information about what will go into your next commit.
Its technical name in Git is the “index”.

## Git directory
Where Git stores the metadata and object database for your project.
This is the most important part of Git, and it is what is copied when you clone a repository from another computer.

# Workflow
1. Modify files in your working tree.
2. Stage just those changes you want to be part of your next commit, which adds only those changes to the staging area.
3. Commit, which takes the files as they are in the staging area and stores that snapshot permanently to your Git directory.

# Credit
Pro Git book, written by Scott Chacon and Ben Straub and published by Apress.
Available here https://git-scm.com/book/en/v2
Licensed under Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported (CC BY-NC-SA 3.0) license.
