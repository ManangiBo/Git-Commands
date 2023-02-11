# Git-Commands
 
## Install/Updates:

 Install Git on your machine 
 ```
 sudo apt install git
 ```
 Check for current Git version
 ```
 git --version
 ```
 
## Settings:
 > SYSTEM = All users
 > GLOBAL = All repositories of the current user
 > LOCAL = The current reposetory
 
 git config --global user.name "Manangi Bo" #Add User Name
 git config --global user.email manangi@gmail.com #Add E-mail to Reposetory
 
 CHANGE TEXT EDITOR
 git config -h/--help
 git config --global core.editor "code --wait"
 git config --global -e = open global settings in default edditor
 
 HOW TO HANDEL END OF LINES
 git config --global core.autocrlf (on Linux or Mac set to "input",on Windows set to "true")
 
 
 cd <folder name/path> = move to directory
 cd .. = move to mother directory (back)
 cd ../../ = move back multible directorys
 
