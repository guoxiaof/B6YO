# work with GitHub on Git Bash

## move to specific folder (U:/)
$ cd U:/

## creat a folder "B6YO" and enter it
$ mkdir B6YO  
$ cd B6YO  

## Initialized empty Git repository in local computer
$ git init 

## checking the status of git
$ git status 
  ~On branch master
  ~No commits yet
  ~nothing to commit (create/copy files and use "git add" to track)
  
## list files in the folder
$ ls   

## add readme.md to staging area
$ git add readme.md 

##comit new changes to local folder
$ git status 
$git commit -m: "Initial commit"  

##check the pass commit and its message
$git log   

## add everything in the folder (instead of one name)
$ git add .  

## add files you want git to ignore
$ touch .gitignore 

## add files to repository in github
$ git remote add orgin http://github.com/guoxiaof/B6YO.git 

##push files to github
$ git push -u origin master 

## any new change 
$git status
$git add .
$git commit -m "xxxmessage"
$git push origin master 
or
$git push
