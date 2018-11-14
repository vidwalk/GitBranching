# GitBranching

# Useful Commands:

Create a branch:

git branch <branchname>

Check the status of your branches and where the HEAD is positioned:

git branch -v

Create a new branch and switch to it:

git checkout -b <branchname>
  
Switch from one branch to another:

git checkout <branchname>
  
Delete a branch:

git branch -d <branchname>
  
To merge a different branch into your active branch:

git merge <branchname>
    
View all the merge conflicts:

git diff

To see where the HEAD is pointing:

git log --oneline –decorate

To see all the branches in a visual manner inside the console:

git log --oneline --decorate --graph --all

Run Git mergetool:

git mergetool


If you mess up, you can replace the changes in your working tree with the last content in head:

git checkout -- <filename>

Changes already added to the index, as well as new files, will be kept.


Instead of dropping all your local changes and commits, fetch the latest history from the server and point your local master branch at it, do this:

git fetch origin

git reset --hard origin/master
