# work with GitHub on Git Bash

$ mkdir B6YO  
#creat a folder "B6YO" at U:/
$ cd B6YO  
#go into folder "B6YO"
$ git init 
#Initialized empty Git repository in U:/B6YO/.git/
$ git status 
#checking the status of git
# On branch master
# No commits yet
#nothing to commit (create/copy files and use "git add" to track)
$ ls   
#list files in the folder
$ git add readme.md 
#add readme.md to staging area
$ git status 
#changes to committed; new file: readme.md
$git commit -m: "Initial commit"  
#commit the change
$git log   
#check the pass commit and its message
$ git add .  
# add everything in the folder
$ git commit -m "xxx" 
#commit all changes
$ touch .gitignore 
# add files you want git to ignore
$ git remote add orgin http://github.com/guoxiaof/B6YO.git 
#add files to repository in github
$ git push -u origin master 
#push files to github

#any new change 
$git status
$git add .
$git commit -m "xxxmessage"
$git push origin master 

#or 

$git push
