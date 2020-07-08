# Github Cheats
## Github basic cheats
To check the git version
`` git --version ``

Git cloning
`` git clone <repository path> ``

Convert a local directory into a repository
 `` git init ``
 
View your remote repositories
 `` git remote -v ``
 
View changes
`` git status ``

View differences
`` git diff [first branch] [second branch] ``

Add commit
`` git commit -m "COMMENT TO DESCRIBE THE INTENTION OF THE COMMIT" ``

## Add Changes
Add a specific file or folder
`` git add <file-name OR folder-name> ``

Add everything
`` git add . ``

## Github push cheats
To push a specific branch
`` git push <remote> <name-of-branch> `` (use remote = origin)

Push all branches
`` git push --all ``

Sends the committed changes of master branch to your remote repository
`` git push [variable name] master ``
`` git push [variable name] [branch] ``

## Github branch cheats

Create and switch to newly created branch:
`` git checkout -b <name-of-branch> ``

Switch to a branch :
`` git checkout <name of branch> ``

Creates branch :
`` git branch name ``

Show all branches
`` git branch --list ``

Merges the specified branch’s history into the current branch
`` git merge [branch name] ``

Delete all changes in branch
`` git checkout . ``

Switch branch
`` git checkout <branch name> ``

Remove selected branch, if it is already merged into any other.
-D instead of -d forces deletion
`` git branch -d [name] ``

Delete branch from remote
`` git push origin :branch-name ``

## Reset to Head
 revert the changes(delete ot modified) that just made and go back to the files that we had
### Hard reset to head
To hard reset files to HEAD on Git, use the “git reset” command with the “–hard” option and specify the HEAD
``  git reset --hard HEAD       (going back to HEAD) ``
``  git reset --hard HEAD^      (going back to the commit before HEAD) ``
`` git reset --hard HEAD~2     (going back two commits before HEAD)  ``
    
To undo a hard reset on Git, use the “git reset” command with the “–hard” option and specify “HEAD@{1}”
`` git reset --hard HEAD@{1} ``




[more commands](https://www.edureka.co/blog/git-commands-with-example/)
 
