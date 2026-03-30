# Git-Github-Learning
this repository is about learning the essentials of git and github
<br>
Author - Github (Learning)

## Git and Github

# Git
The Version Control System is a tool that helps to track changes in the code
- The Git is a version control system, and it is:
. Popular
. Free and Open Source
. Fast & Scalable.

-- Further it also helps with tracking the history, collaborating, etc.

# Github
Now Github is a website that allows developers to store and manage their code by using the Git.

http://github.com

# Clone & Status
- Clone: its the process of cloning a repository in the local machine.
<br>
  git clone <- some link ->
  
- Status: this displays the state of the code.
<br>
  git status

 - ls -> this means listing all files.
 <br>
 - ls -a -> this gives hidden files also, means it shows all the files, which in normal circumstances dont get showed.
 . this ls -a command is for git bash, but for simple powershell use in the vscode the relevant command to ls -a is:

  Get-ChildItem -Force

 -- Types of Statuses
 . There are four main types of statuses:

 1: Untracked:
 . These are the new files which are not yet tracked by the git.
 <br>
 2: Modified:
 . it means being changed
 <br>
 3: Staged:
 this means the file which is ready to be committed
 <br>
 4: Unmodified:
 So as the name suggests this means not changed yet.
 <br>

 ## Key Commands:

 # add:
 git add <- file name ->
 <br>
this helps in adding or changing the files in the directory where work is going on.
<br>

# commit:
git commit -m 'any message'
<br>
it is explained as keeping the record of changes.
<br>

# push:
git push origin main
this command is used for the purpose of uploading the local repo. content to the remote repo.
<br>

- push:
git push origin main
. this command is used for the purpose of uploading the local repo. content to the remote repo.

- Init
 git init
<br>
the init command is used to create a new repo.
<br>
git remote add origin <- link ->
<br>
git remote -v (to verify remote)
<br>
git branch (to check branch)
<br>
git branch -M main (to rename the branch)
<br>
git push origin main

# WorkFlow
- Local Git
in local git the general flow is:
 github repo -> clone -> changes -> add -> commit -> push 

 ## Git Branches

 # Branch Commands
 git branch -> (to check the branch)
 <br>
 git branch -M main -> (to rename the branch)
  <br>

# WorkFlow

- Local Git
. in local git the general flow is: github repo -> clone -> changes -> add -> commit -> push

## Git Branches

# Branch Commands

git branch -> (to check the branch)
<br>
git branch -M main -> (to rename the branch)
<br>
git checkout <-branch name-> (to navigate, like moving from one branch to another)
<br>
git checkout -b <-new branch name-> -> (used to create the new branch)
<br>
git branch -d <-branch name-> -> used to delete the branch

## Merging Code:
# Way 1
git diff <- branch name ->  (this is used to compare commits, branches, files and more)
<br>
git merge <-branch name ->  (used to merge the 2 branches)

Way 2
Create a PR -> this means a pull request

# Pull Request:
it lets you tell others about changes that are pushed to a branch in a repository on GitHub.
<br>

# Pull Command:
git pull origin main

. this command is used to fetch and download the content from a remote repo and then immediately update the local repo in order to match the content.

# Resolving Merge Conflicts:
Its a event that takes place when git is unable to automatically resolve the differences in code b/w the two commits.



