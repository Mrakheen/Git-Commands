Git Commands
============

_A list of Git commands_
--

___
___

### Tell Git who you are

| Description | Command |
| ------- | ----------- |
| Configure the author name.|`git config --global user.name "<username>"`|
| Configure the author email address.|`git config --global user.email <email address>`|


### Getting & Creating Projects

| Description | Command  |
| ------- | ----------- |
| Initialize a local Git repository | `git init` |
| Create a local copy of a remote repository | `git clone ssh://git@github.com/<username>/<repository-name>.git` |


### Basic Snapshotting

| Description | Command |
| ------- | ----------- |
| Check status | `git status` |
| Add a file to the staging area | `git add <file-name.txt>` |
| Add all new and changed files to the staging area | `git add -A` or <br> `git add .` |
| Commit changes | `git commit -m "<commit message>"` |
| Remove a file (or folder) | `git rm -r <file-name.txt>` |



### Inspection & Comparison

| Description | Command |
| ------- | ----------- |
| View changes | `git log` |
| View changes (detailed) | `git log --summary` |
| View changes in one line (briefly) | `git log --oneline` or <br> `git log --pretty=oneline` or<br> `git log --pretty=short` |



### Undo to previous file

| Description | Command |
| ------- | ----------- |
| List of all commit with commit id and commit message) | `git log --oneline` |
| Return to previous commit <commit id> | `git checkout<commit id>` |
| Revert commit <commit id> (undo one particular commit) | `git revert <commit id>` |
| Reset to previous commit <commit id> (remove history of all commit after <commit id> ) | `git reset --hard <commit id>`|
| Stop a file being tracked | `git rm --cached <file/folder>` |
| Restore a file to a previous commit| `git checkout <file/to/restore>` |



### Branching & Merging

| Description | Command |
| ------- | ----------- |
| List branches (the asterisk denotes the current branch) | `git branch` |
| List all branches (local and remote) | `git branch -a` |
| Create a new branch | `git branch <branch name>` |
| Create a new branch and switch to it | `git checkout -b <branch name>` |
| Clone a remote branch and switch to it | `git checkout -b <branch name> origin/<branch name>` |
| Rename a local branch | `git branch -m <old branch name> <new branch name>` |
| Switch to a branch | `git checkout <branch name>` |
| Switch to the branch last checked out | `git checkout -` |
| Discard changes to a file | `git checkout -- <file-name.txt>` |
| Delete a branch | `git branch -d <branch name>` |
| Delete a remote branch | `git push origin --delete <branch name>` |
| Preview changes before merging | `git diff <source branch>  <target branch>` |
| Merge a branch into the active branch | `git merge <branch name>` |
| Merge a branch into a target branch | `git merge <source branch> <target branch>` |
| Stash changes in a dirty working directory | `git stash` |
| Remove all stashed entries | `git stash clear` |


### Sharing & Updating Projects

| Description | Command |
| ------- | ----------- |
| Push a branch to your remote repository | `git push origin <branch name>` |
| Push changes to remote repository (and remember the branch) | `git push -u origin <branch name>` |
| Push changes to remote repository (remembered branch) | `git push` |
| Push changes to remote repository all branch | `git push --all` |
| Push changes to remote repository (Force) | `git push -f` |
| Delete a remote branch | `git push origin --delete <branch name>` |
| Update local repository to the newest commit | `git pull` |
| Pull changes from remote repository | `git pull origin <branch name>` |
| Add a remote repository | `git remote add origin ssh://git@github.com/<username>/<repository-name>.git` |
| Set a repository's origin branch to SSH | `git remote set-url origin ssh://git@github.com/<username>/<repository-name>.git` |



## Contributing to Open - Source - Software (OSS)

![Screenshot 2024-02-13 164912](https://github.com/Mrakheen/Git-Commands/assets/53326887/ab670d0f-7e79-416f-8b03-eee42eb0f2cb)

![Screenshot 2024-02-13 165759](https://github.com/Mrakheen/Git-Commands/assets/53326887/b12c1217-450a-413c-b2b3-4bd9d3d34b9e)

![Screenshot 2024-02-13 165905](https://github.com/Mrakheen/Git-Commands/assets/53326887/6fac04ae-2b34-4cc2-afbb-44d68fbb861f)

![Screenshot 2024-02-13 170009](https://github.com/Mrakheen/Git-Commands/assets/53326887/46066258-f01a-4fff-91da-befd60210d2a)

![Screenshot 2024-02-13 170030](https://github.com/Mrakheen/Git-Commands/assets/53326887/8cefe0ff-ec31-4d3f-91ed-0c57a88aa19a)

![Screenshot 2024-02-13 170200](https://github.com/Mrakheen/Git-Commands/assets/53326887/03cb8922-713f-4914-abab-a92d4416e1c7)

![Screenshot 2024-02-13 170320](https://github.com/Mrakheen/Git-Commands/assets/53326887/53b5b64e-3699-4e24-8d12-888b79811408)

![Screenshot 2024-02-13 170750](https://github.com/Mrakheen/Git-Commands/assets/53326887/774f163c-ce82-4730-a7f9-25c71e790f6c)
