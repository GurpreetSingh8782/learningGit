1.`git init`:- Powers your folder to be managed by git, and initialize a new empty repository.It also creates a .git folder that has all the relevant logic to manage the versions of your project.

2.`Working area`:- There can be a bunch of files that are not currently handledby git.
It means that changes can be done in those files that are not managed by git yet.A file which is in working area is considered to be not in the staging are. When we do git status and see bunch of 'Untracked file' then these are actually called to be in the working area.

3.`Staging Area`:- what all files are going to be the part of the next versions that we will create.This staging area where git knows what changes will be done from the last version to the next version.

4.`Repository area`:-This area actually contains the details of all your previous registered versions, and all the files in this area, git already manages them and knows their version history.

5.`git add <file>`:-moves file from working area to staging area

6.`git rm --cached files`:-moves file back from staginga area to working area

7.`commit`:- Commit is a particular version of the project. It captures a snapshot of the project's staged changes and creates a version of it.

8.`git commit`:-registers staging changes to a commit 

9.`git log`:- lists down all the commit in the repository.if you want to exit out of git log just enter 'q'

10.`git restore <file>`:-it remove all files changes from the staging area to be commited. This can be useful, if we did some dirty piece of code and now no more want it. Instead of deleting every change line by line, we can restore it or you can restore last clean version of the file 

11.`git restore --staged <file>`:-it removes file from staging area to working area.This only works if changes are in your staging area.

12.Diff between git rm and git restore
ans:If you want to move the whole file back to the Untracked state, then we do git rm,otherwise if we just want the changes from working area to staging area and vice-versa then we use git restore   

13.`git remote`:- list down all the remote connection names

14.Remote connection:- It helps you to link two git repositories for uploading and downloading changes from each others.

15.`git remote add <name of the remote> <link of the remote>`:- this command helps us to add a new link to the remote repo and give name to it

16.`git remote rm <name of the remote`:- this command deletes a remote connection

17.`git remote rename <oldname> <newname>`: this command renames the remote connection

Note:The name of the remote connection is always used to establish communication between repos.