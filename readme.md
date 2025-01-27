# HELLO PROFESSOR
THIS IS MY HOMEWORK 1 FOR THE IS601 WEB SYSTEMS DEVELOPEMENT COURSE

# INSTUCTIONS FOR HOMEWORK 1: INSTALL WSL2 WITH UBUNTU FOR WINDOWS, FOR MAC OS LINUX IS ALREADY PRESENT
-> STEP 1: INSTALL GIT AND SETUP GIT IN THE TERMINAL <br/>
-> STEP 2: CREATE A SEPARATE FOLDER FOR HOMEWORK <br/>
-> STEP 3: INITIALIZE GIT IN THE CREATED FOLDER<br/>
-> STEP 4: CREATE README AND GITIGNORE FILES AND MAKE COMMITS <br/>


# # OTHER INSTRUCTIONS:
-> STEP 1: CREATE A SECOND BRANCH <br/>
-> STEP 2: MAKE CHANGES IN THE README AND GITIGNORE FILES AS NEEDED AND MAKE COMMITS <br/>
-> STEP 3: CHECKOUT TO THE MASTER BRANCH AND MERGE THE CREATED SECOND BRANCH <br/>
-> STEP 4: PUSH THE MASTER BRANCH

# COMMANDS

git
mkdir IS601_PROJECTS_2025
cd IS601_PROJECTS_2025
mkdir HOMEWORK1
cd HOMEWORK1
pwd
git init
touch readme.md
git status
touch .gitignore
git status
ls -a
git add readme.md
git commit -m “Added a readme file”
git add .gitignore
git commit -m “Added a gitignore file”
git status
git log
git checkout -b Updatereadme
git status
vi readme.md
git commit -am “Updated the readme file”
git status
vi .gitignore
git add .
git status
git commit -m “Updated the gitignore file with swap files”
git checkout master
ls
git status
git merge Updatereadme
git log
git status
git remote add origin git@github.com:Krishna-Sathvika-Ganni/IS601-HOMEWORK1.git
git remote show
git remote show origin
git push origin master
git checkout -b Instructions
vi readme.md
git commit -am “Updated the readme file with instructions”
vi .gitignore
git commit -am “Updated the gitignore file with swo files”
git log
git push origin Instructions
git fetch
git checkout master
git pull origin master
vi readme.md
git commit -am “Made a few changes to the instructions in readme file”
git push origin master
git checkout -b OtherInstructions
vi readme.md
git commit -am "Added other instructions to the readme file"
git push origin OtherInstructions






