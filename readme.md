# HELLO PROFESSOR
THIS IS MY HOMEWORK 1 FOR THE IS601 WEB SYSTEMS DEVELOPEMENT COURSE

# INSTUCTIONS FOR HOMEWORK 1: INSTALL WSL2 WITH UBUNTU FOR WINDOWS, FOR MAC OS LINUX IS ALREADY PRESENT
-> STEP 1: INSTALL GIT AND SETUP GIT IN THE TERMINAL <br/>
-> STEP 2: CREATE A SEPARATE FOLDER FOR HOMEWORK <br/>
-> STEP 3: INITIALIZE GIT IN THE CREATED FOLDER<br/>
-> STEP 4: CREATE README AND GITIGNORE FILES AND MAKE COMMITS <br/>


# OTHER INSTRUCTIONS:
-> STEP 1: CREATE A SECOND BRANCH <br/>
-> STEP 2: MAKE CHANGES IN THE README AND GITIGNORE FILES AS NEEDED AND MAKE COMMITS <br/>
-> STEP 3: CHECKOUT TO THE MASTER BRANCH AND MERGE THE CREATED SECOND BRANCH <br/>
-> STEP 4: PUSH THE MASTER BRANCH

# COMMANDS

git <br/>
mkdir IS601_PROJECTS_2025 <br/>
cd IS601_PROJECTS_2025 <br/>
mkdir HOMEWORK1 <br/>
cd HOMEWORK1 <br/>
pwd <br/>
git init <br/>
touch readme.md <br/>
git status <br/>
touch .gitignore <br/>
git status <br/>
ls -a <br/>
git add readme.md <br/>
git commit -m “Added a readme file” <br/>
git add .gitignore <br/>
git commit -m “Added a gitignore file” <br/>
git status <br/>
git log <br/>
git checkout -b Updatereadme <br/>
git status <br/>
vi readme.md <br/>
git commit -am “Updated the readme file” <br/>
git status <br/>
vi .gitignore <br/>
git add . <br/>
git status <br/>
git commit -m “Updated the gitignore file with swap files” <br/>
git checkout master <br/>
ls <br/>
git status <br/>
git merge Updatereadme <br/>
git log <br/>
git status <br/>
git remote add origin git@github.com:Krishna-Sathvika-Ganni/IS601-HOMEWORK1.git <br/>
git remote show <br/>
git remote show origin <br/>
git push origin master <br/>
git checkout -b Instructions <br/>
vi readme.md <br/>
git commit -am “Updated the readme file with instructions” <br/>
vi .gitignore <br/>
git commit -am “Updated the gitignore file with swo files” <br/>
git log <br/>
git push origin Instructions <br/>
git fetch <br/>
git checkout master <br/>
git pull origin master <br/>
vi readme.md <br/>
git commit -am “Made a few changes to the instructions in readme file” <br/>
git push origin master <br/>
git checkout -b OtherInstructions <br/>
vi readme.md <br/>
git commit -am "Added other instructions to the readme file" <br/>
git push origin OtherInstructions <br/>






