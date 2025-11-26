# Git Commands

## git add
Moves changes from the working directory to the staging area.  
This gives you the opportunity to prepare a snapshot before committing it to the official history.  

*git add <file>* - add a single file  
```git add index.html``` 
This file will be included in the next commit.  

*git add directory/* - add a folder.

*git add .* - add everything in the current directory.

*git add -A* - add absolutely everything, including deleted files

*git add -u* - update tracked files only (does NOT add new files) 

*git add -p* - interactive patch mode (add changes piece by piece, in parts)

*git add -i* - interactive menu mode (opens a text-based menu where you can choose what to stage)

*git add "*.txt"* - add files by pattern

*git add -N file OR git add --intent-to-add* - Git starts tracking the file(s) without actually staging its contents.


