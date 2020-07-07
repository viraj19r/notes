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
 
* create a branch
  * git checkout -b <name-of-branch>
* switch to a branch
  * git checkout <name of branch>
* view changes
  * git status
* view differences
  * git diff [first branch] [second branch]
* add changes
  * git add <file-name OR folder-name>
* add commit
  * git commit -m "COMMENT TO DESCRIBE THE INTENTION OF THE COMMIT"
* Add all changes to commit
  * git add .
  * git commit -m "COMMENT TO DESCRIBE THE INTENTION OF THE COMMIT"
* git push <remote> <name-of-branch>
* Delete all changes in branch
  * git checkout .
* Unstage all changes that have been added to the staging area
  * git reset .
* git push --all
* git push [variable name] master = This command sends the committed changes of master branch to your remote repository.
*  git push [variable name] [branch]
* git branch name 
* git checkout branch name =creates a branch
* git branch -b name =creates and switch to branch
* git merge [branch name] = This command merges the specified branch’s history into the current branch.
* git branch -d [name]  = Remove selected branch, if it is already merged into any other.
-D instead of -d forces deletion

* git branch --list =  it will show all branches
* git fetch -p = shows last deleted branch
* git branch –D branch-name (delete from local)
* git branch -d -r [name] = to delete from local as well as remote(github) =not worked for remote
* git push origin :branch-name (delete from remote)


  
[more commands](https://www.edureka.co/blog/git-commands-with-example/)
 
