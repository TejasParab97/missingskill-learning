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
 * Once, you successfully crearted account , Go to New Project and give suitable name for your project and do configurations.
 * Then , create a folder in your local system to save Git repository's files.
 * Once, you created folder, If you are using Linux machine then you can do it on Terminal. but, if you are windows user, then you need to use GitBash.
 * Now, redirect to your repo's directory/folder through termianl which you just created
 Type, **git init** .
 this command will create a hidden folder named **.git** in your repo's folder just like shown in below image:
  >If you use ls -la, then this folder visible to you.

  <br>
  <img src="Images and Screenshots/git commands/git init.png">

* Now , add the files in the folder whichever you want add some content in it. and then, again go to your terminal/Console window and enter the command:

```
git status
```
 <br>

   
  
this command will check your repo's status. so, just now you created some files and made some changes in it then, terminal shows you a message as untracked file and it will show you the name of the file you added or modified in red color like below image


<br>
<img src="Images and Screenshots/git commands/git_status untracked file.png">

 <br>
 <br>



* Now, if you want to add changes to your remote server and to track your modified or newly added file enter following command:

 ```
 git add <file-name>
 ```

   If you want to add all files then enter:

```
git add .
```
<br>

this command will add all the modified files into your repository. and now file status is changed from untarcked to tracked.now , if you enter **git status** then, you will see prviously shown filename shown in red turned into green. that means now your file successfully tracked on server.

<br>
<img src="Images and Screenshots/git commands/git_status tracked file.png">

<br>
<br>

* Now , you will see on above image your files are tracked bit there is message i.e. changes to be commited that means all the changes you made in your file are still not commited so, if you want to commit the changes, then enter following command:

```
git commit -m "changes commited"
```

<br>

this command will commits all the changes you have made.

<br>
<img src="Images and Screenshots/git commands/register file in git repo.png">

<br>
<br>

* Now, if you enter **git status** command, you will see a message '_your branch is ahead of origin-master_'. here, **origin** is server & **master** is your branch. 
<br>
<img src="Images and Screenshots/git commands/git status after commit.png">

<br>

* now , if you want to push changes to your origin-master branch , then enter following command:

```
git push origin master
```

<br>

<img src="Images and Screenshots/git commands/git push origin master.png">

<br>

*now , all your files are updated on your master branch to verify that, re-enter the **git status** command, now you can see the message i.e. '_your branch is up to date with origin/master_'.

<br>


<img src="Images and Screenshots/git commands/git status after register file.png">

<br>
<br>
<br>

<img src="Images and Screenshots/Git flow.jpg">

<br>
<br>

---

<br>

* git show:

  This command is shows log of changes we made in file by using commit id reference of specific commit.



  <img src="Images and Screenshots/git commands/git show.png">

  <br>
  <br>

* git branch commands:
  
  * git branch:
     
     lists all the branches available in repository.

  * git branch <branch_name>:

    create a new branch in repository.

    <img src="Images and Screenshots/git commands/git-create new branch.png">

    <br>

  * git checkout <branch_name>;

    switch between two branches.

    <img src="Images and Screenshots/git commands/git status after register file.png">

    <br>
    <br>

* git log:

  lists all the changes commited in repository and each commit has special commit id.

  <img src="Images and Screenshots/git commands/git_log.png">




      



