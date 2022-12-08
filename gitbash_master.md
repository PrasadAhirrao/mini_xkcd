# below steps to upload project on Github
- check current path
- nevigate to project path
- git config username & email
- create repository on Github account
- git init
- git config --list
- git status
- create .gitignore file in project
- add file
- commit
- git remote add origin https://github.com/python10sep/mini_xkcd.git 
- git push -u origin master OR git push origin master
==============================================================================
pwd - to check current path. present working directory
cd <path> - to change path 

# if we are at path '/c/users/Admin/' and you have to go deep in same path then - 
cd ~/<deep path>/

ls
ls -la
git config --global user.name "prashant"
git config --global user.email "prashant@gmail.com"
# create repository on your Github Account of project name
git init
git config --list
git status

# create a file `.gitignore` - 
*.pyc
*.xml
venv
*.log
.idea

git add <file-name>
git add --all

# git add --all --> Unstage area --> commit --> stage area -->
git commit -m "<commit-message>"

# if accidentally only `git commit` command run then follow below steps.
step 1 - press exc
step 2 - :q!
step 3 - press enter

# run git log to see commit id and commit message history
git log 

# URL from Github project repository
git remote add origin https://github.com/python10sep/mini_xkcd.git 
git push -u origin master OR git push origin master
=================================================================================
# clone project from others github in your system
step1 - navigate to project root
cd <path>
step2 - This step will create a directory called `.git`.
git init
step3 - By default `git clone` command will download `master` copy from github.
git clone <HTTP URL>

# After clone to upload this project on your github account.
step1 - nevigate to clone project directory
cd <path>
step2 - show url associated with clone project. The label associated with URL is called 'origin'
git remote -v
step3 - create repository of project on github account
step4 - to change URL
git remote set-url origin <url from project repository of my github account>
step5 - check you are on master branch
step6 - final step
git push origin master

# alternate way to do this from Github
go to my repo on github, click on FORK

================================================================================

# to pull the latest changes done by others from master branch of your github in your system 
git pull origin master

# steps for producing merge conflicts.
step1 - nevigate to project command which already uploaded on github
cd <path>
step2 - to check branch. ensure that u r on master branch. below command to list all branches.
git branch -a
step3 - if not in master branch, to checkout to master branch
git checkout master
step4 - 







