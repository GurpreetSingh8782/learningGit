1.`git init`:- Powers your folder to be managed by git, and initialize a new empty repository.It also creates a .git folder that has all the relevant logic to manage the versions of your project.

2.`Working area`:- There can be a bunch of files that are not currently handledby git.
It means that changes can be done in those files that are not managed by git yet.A file which is in working area is considered to be not in the staging are. When we do git status and see bunch of 'Untracked file' then these are actually called to be in the working area.

3.`Staging Area`:- what all files are going to be the part of the next versions that we will create.This staging area where git knows what changes will be done from the last version to the next version.

4.`Repository area`:-This area actually contains the details of all your previous registered versions, and all the files in this area, git already manages them and knows their version history.

5.`git add <file>`:-moves file from working area to staging area

6.`git rm --cached files`:-moves file back from staginga area to working area

7.`commit`:- Commit is a particular version of the project. It captures a snapshot of the project's staged changes and creates a version of it.

8.`git commit`:-registers staging changes to a commit