# Git and GitHub basics
### Git:
---
-Git is a version control system that track changes in our code. <br>
-It allows multiple people to work on a project at the same time.  <br>
- Popular
- free and open source
- fast and scalable

### GitHub:
---
-GitHub is a popular platform use for storing our works. It is a cloud based platform that uses Git to store, manage, and share code. <br>
-It allows developers to collaborate, track changes adn work together on projects.
-Aleternate of Github is Gitlab and Bitbucket more..

### Repository:
---
-A Git repository(repo) is a storage space where our entire project file and their enitre changes history are kept. <br>
-Repo is like a ***folder*** that store all changes in our projects.
#### Local Repo:
-Local repo exists on our own conputer. <br>
-It contains our project files and the full git history. <br>
-It is created by using
>git init
#### Remote Repo:
-It exist on the internet or a server, usually hosted on platforms like:
  - GitHub
  - GitLab
  - Bitbucket      <br>
-Connected using 
>git remote add origin <repository_url>

- Tracked Repo
-Git can tracked these files.

<br>

- Untracked Repo
  
 -means git can not track these files.
 -Or new files that git doesn't tracked yet.

<br>

- modified
  <br>
  
- unmodified
  file is unchanged.
  <br>
  
- staged
-file is ready to commit.
### To generate an account on GitHub go to https://github.com

-Create your accound by giving the required details.
<br>
-Then create your account.
### To create a new repo
-Sign in to your account tap new repo. 
<br>
-Give your repo name.
<br>
-Then select public or private according to you.
<br>
-Add readme.md(here md means markdown) for details.
<br>
-Then tap create.


### Setting up Git
-It work on our system.
<br>
-Download VS code.
<br>
-for Windows (Git Bash)
<br>
-for mac(Terminal)
<br>
-For Verify run
>git --version

#### Configuring Git
-To config git we write 
<br>
>git config --global user.name"my_Name"
<br> <br>
>git config --global user.email"shaoodell@email.com"<br><br>
---

-To see all configuration setting run 
<br>
>git config --list

### Commit:
-It saved our changes with message.

### Clone:
-Cloning a repository on our local machine
>git clone <---put the link here.....>

### To move inside another folder <br>
> cd folderName
>
<br>
-To clear terminal
> clear <br>
<br>

-To watch all file list
> ls <br>

-To watch all file including out hidden file  <br>
> ls -a <br>

### Complete Git flow:
![img1.png](img1.png)

### ADD and Commit
- ***ADD:***
  -adds new or changed files in your working directory to the git staging area.
   <br>
  >git add <-fileName-->  or simply [git add.] (for all file at a time)
  <br>
- ***Commit:***
  >git commit -m "some message"
<br>
### Push Command
-Upload local repo content to remote repo.<br>
>git push origin main

## To start with our local repo
- init: used to create a new git repo <br>
- git remote add origin <---link....> <br>
- git remote -v (to verify remote)
- git branch (to check branch)
- git branch -M main (to rename branch)
- git push origin main



