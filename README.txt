1. `git init` -> powers your folder to managed my git, and initialise a new empty respository.
It also create a .git folder that has all relevent logic to manage versions of your project.

2. `working area` -> there can be bunch of files that are not currently handled b git.
It means that changes done or to be done in those files are not managed by git yet. A file which is in 
working area is considered to be not in staging are. When we do git status we see bunch of `untracked file`
then these are to be inthe working are

3. `staging area` -> what are files which are going to be part of next version that we will create.
This staging area is the place where git knows what changes will be done from last version to next version.

4. `respository area` -> this area actually contains the detail of your previous regestired version
and file in this area, git already manages then and knows there version history.

5. `git add <file>` ->  move file from working area to staging area
6. `git rm --cached <file>` -> move file from staging area to working area  

7. `commit` -> commit is a particular version of the project. It captures a snapshot of the project's stages changes
and creates version out of it.

8. `git commit` -> register staging changes to  a commit
