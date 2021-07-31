# Git

### **(1) WHAT IS GIT?**
<br>

* Git is an open source tool for Documentation of very large projects in most efficient way. Generally, Git stands for **Global Information Tracker**.


* Git is used by developers to collabrately work on source code of softwares.

<br>


---
<br>

### **(2) WHY USE GIT?**
<br>

* If you working on a big project in large organizations , then using Git tool is must. you cannot build projects without Git.


* Multiple developers or programmers can work on same project at the same time.


* Git tool is **distributed** beacuse of that, different developers form different locations can manage source code from anywhere.


* the best part about Git is, if somehow developer accidentally lost his working source code from his local machine , still he can recover source code from server where repositories are stored.

<br>

---
<br>

### **(3) GIT BASIC COMMANDS**
<br>

|Commands  |Function |
|:--------- | :--------: |
|git init .|Creates a git repository in local system. add repository folder and add .git folder i.e. hidden folder.|
|rm -rf git|Removes the git repository.|
|touch (filename)|Adds new file in Git repository.|
|cat > (filename)|Update the content of the file.|
|git add|Add Untracked file into repository. |
|git commit|All tarcked files changes are commited.|
|git status|show the status of files in repository.|
|git diff|If you add some changes in file then before adding the file you can see the log of changes you have made.|
|git log|Gives the log of all commited changes|
|git show (commit_id)|every changes commited has special commit id so we can retrieve specific commit details. |
|git push origin master| Commited changes are pushed to server in master branch.|
|git pull origin master|All changes made in server are automatically applied on local machine too.
|git branch|Lists all the branches available in git repository.|
|git branch (branch_name)|Adds new branch in git repository.|
|git checkout (branch_name)|Switch between multiple branches. |
|git branch (branch_name) d|Delete specific Branch|
|git checkout (file_name)|Recovers deleted files which are stored in git repository.|
|git merge (branch_name)|To merge one branch with another branch.|
|git reset HEAD (file_name)|Unstage the added file before commit the file changes.|
|git stash|If you add some changes but , you do not want to commit the changes then this command creates a copy of your git repo and save it somewhere for later use.|
|git stash pop|Open your stashed repo and you can work with your uncommited files.|
|git stash list|Lists all the stash files which is uncommited.|

---

<br>


 ### **(4) GIT WORKFLOW**

 * To Create a new repository for your work first you need to create your own account on **GITLAB** _Or_ **GITHUB**. These services will  help you to store your project files on server.
