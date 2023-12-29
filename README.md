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

5. `git add <file>` -> move file from working area to staging area
6. `git rm --cached <file>` -> move file from staging area to working area

7. `commit` -> commit is a particular version of the project. It captures a snapshot of the project's stages changes
   and creates version out of it.

8. `git commit` -> register staging changes to a commit.
9. `git log` -> list all the commits of the respository.

10. `git restore <file>` -> remove all files changes from staging area to be commited.
    This Can be use full if we did some dirty pieces of code and no more want it. inseted of deleting every line bye line,
    we can restore last clean version of the file.

11. `git restore --staged <file>` -> it removes files from staging area to working area
12. difference between git rm and git restore
    ans : if you want to move whole file back to untracked file, we do git rm
    if you just want to move in working area or staging area we do git git restore

13. `git diff commit1 commit2` -> gives difference of all files changes
14. `git commit -m <commit_msg>` -> commit without opening vim editior
15. `git remote` -> list down all the remote connections names
16. remote connection -> It helps you to link two git repositories for uploading and downloading changes
    from each other

17. `git remote add <remote name> <link of remote>` -> this command helps us to add a new link to the remote repositories
    and give a name to it

18. `git remote rm <name of remote>` : this command delete a remote connection
19. `git remote rename <oldname> <newname>` : this command renames the remote connections

Note: The name of the remote connections is always used to established communication between the repositories

20. `git add <file1> <file2> <file3>` -> this commamd will add multiple files in staging area
21. `git add .` : add all files from working repos to staging area

22. `git pull <remote name> <branch name>` : downloads the latest changes from the branches of the mentioned remote in your local repos
