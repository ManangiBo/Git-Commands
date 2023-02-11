# Git-Commands
 
## Install/Updates:

 Install Git on your machine: 
 ```
 sudo apt install git
 ```
 Check for current Git version:
 ```
 git --version
 ```
 
## Settings:
 > **SYSTEM _= All users_**
 > 
 > **GLOBAL _= All repositories of the current user_**
 > 
 > **LOCAL _= The current reposetory_**
 
 Add User Name to Reposetory:
 ```
 git config --global user.name "Manangi Bo" 
 ```
 Add E-mail to Reposetory:
 ```
 git config --global user.email manangi@gmail.com
 ```
 
 **CHANGE TEXT EDITOR**
 ```
 git config -h/--help
 git config --global core.editor "code --wait"
 git config --global -e = open global settings in default edditor
 ```
 HOW TO HANDEL END "OF LINES"
 ```
 git config --global core.autocrlf true
 ```
 (on Linux or Mac set to "input",on Windows set to "true")
 
 
 move to directory
 ```
 cd <folder name/path> 
 ```
 move to mother directory (back)
 ```
 cd ..
 ```
 move back multible directorys
 ```
 cd ../../
 ```
 
## Commit:

 get status
 ```
 git status
 ```
 add all
 ```
 git add . 
 ```
 add sertin format
 ```
 git add *.md
 ```
 Remove File
 ```
 git rm --cached <file name>
 ```
 Commit changes to reposetory
 ```
 git commit
 ```
 `git commit` opens up the vim edditor to enter a comment, wenn you start typing it is not    going to do anything, type `i` to go into insert mode, now type your comment. Now to Exit press`Esc` to get out of insert mode and type in `:wq`
