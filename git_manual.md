#Git Commands
-git init
to create local repo.

-git clone
to clone or download the git hub repo.

-git remote add origin <https link>
to add remote repo.

-git remote --verbose
gives the urls(https) to which our foldres are linked to.

-git remote set-url origin <https link>
this resets the origin url, with new url we have mentioned.

--
-git pull
to pull files from central repo.

-git push
to push your changes into central repo.

-clear
to clear the screen.

-git pull origin master/main
to pull all the files in that repo.

-git status
tells you which files are added to the index and are ready to commit.

-git add filename.format
lets you to add file to the index.

-git commit -m "commit message"
commits the files or changes of the user to the central repo from the index.
Note: if the files were added once to the index , we need not add it everytime while modifing before
commiting, we can directly use commit -a -m.

-git add -A
add all the files in the folder.

-git reset <file>
undo the add command.

-git commit -a -m "commit message"
to commit all the files added to the index.
Note: if the files were added once to the index , we need not add it everytime while modifing before
commiting, we can directly use commit -a -m.

-git log
the log of when and how the files are stored.

-git branch BranchName
creates a new branch.

-git chechout BranchName
moves to that branch.

-ls
lists out all the files in that branch.

-git merge BranchName
it merges all the files of specified BranchName into the brach you are currently at.
so we must checkout to the branch were we want to merge the files.

-cat filename.format
status  of the file.

-git rebase BranchName
this will do the same as merge but in a linear way.checkout to the branch you want to update.
 
- ssh-keygen
to generate ssh key

-ssh -T git@github.com
for authenticating the ssh key.

-git push origin BranchName
pushes all the commited changes of the current branch into the specified branch.

-git switch -f <branch-name>
switches to the mentioned brach even without commiting the changes made in the other branch.

-git switch --orphan newBranch
creates a empty branch.

-git branch
this will list out all the local branches we have.

-git branch -D BranchName
this command deletes the mentioned branch in local.

-git branch | grep -v "main" | xargs git branch -D
this deletes all the local branches excep the main branch, we can also add other branches which we want
to keep , along with the main branch.
__________________________ 






























