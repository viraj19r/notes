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

## Github branch cheats

Create a branch:
`` git checkout -b <name-of-branch> ``

Switch to a branch
`` git checkout <name of branch> ``

Creates and switch to newly created branch
`` git branch -b name ``

Show all branches
`` git branch --list ``

Merges the specified branch’s history into the current branch
`` git merge [branch name] ``


* Delete all changes in branch
  * git checkout .
* git push [variable name] master = This command sends the committed changes of master branch to your remote repository.
*  git push [variable name] [branch]
* git branch name 
* git checkout branch name =creates a branch
* git branch -d [name]  = Remove selected branch, if it is already merged into any other.
-D instead of -d forces deletion
* git fetch -p = shows last deleted branch
* git branch –D branch-name (delete from local)
* git branch -d -r [name] = to delete from local as well as remote(github) =not worked for remote
* git push origin :branch-name (delete from remote)

[more commands](https://www.edureka.co/blog/git-commands-with-example/)
 
