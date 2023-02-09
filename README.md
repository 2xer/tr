# File states
## Modified
File modified but not committed
## Staged
File modified and will be in the commit snapshot
## Committed
File is stored in the local database

# Project sections
![Project sections image](/screenshots/project-sections.png?raw=true)
## Working tree
A single checkout of one version of the project.
These files are pulled out of the compressed database in the Git directory and placed on disk for you to use or modify.
## Staging area
File, generally contained in your Git directory, that stores information about what will go into your next commit.
Its technical name in Git is the “index”.
## Git directory
Where Git stores the metadata and object database for your project.
This is the most important part of Git, and it is what is copied when you clone a repository from another computer.

# Credit
Pro Git book, written by Scott Chacon and Ben Straub and published by Apress.
Available here https://git-scm.com/book/en/v2
Licensed under Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported (CC BY-NC-SA 3.0) license.
