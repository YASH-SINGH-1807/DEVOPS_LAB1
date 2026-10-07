# DevOps Lab Command Log

# for ubuntu/linux------------------------------------------------------
## Git Installation

sudo apt update

sudo apt install git -y

git --version

## Git Configuration

git config --global user.name "YASH SINGH"

git config --global user.email "example@gmail.com"

git config --list

## Repository Setup

git init

git add .

git commit -m "Initial Commit"

git branch

git checkout -b feature

git merge feature

git push origin main

## Jenkins Installation

sudo apt install jenkins -y

sudo systemctl start jenkins

sudo systemctl status jenkins

## Jenkins Pipeline

Build Now

Console Output

Pipeline Stages


# for CMD -----------------------------------------------------------------

## Git Verification

git --version

## Git Configuration

git config --global user.name "YASH SINGH"

git config --global user.email "your_email@gmail.com"

git config --list

---

## Repository Setup

mkdir Devops_Lab1

cd Devops_Lab1

git init

---

## Create Project Files

mkdir screenshots

mkdir reports

echo. > README.md

echo. > Jenkinsfile

---

## Git Operations

git status

git add .

git commit -m "Initial Commit"

git branch

git checkout -b feature

git checkout master

git merge feature

git log --oneline

---

## GitHub Connection

git remote add origin https://github.com/YASH-SINGH-1807/DEVOPS_LAB1.git

git remote -v

git push -u origin master

git push origin master

---

## Jenkins Verification

sc query jenkins

java -version

---

## Jenkins Pipeline Configuration

1. Open Jenkins Dashboard
2. Click New Item
3. Select Pipeline
4. Configure Pipeline Script from SCM
5. Enter GitHub Repository URL
6. Save Job
7. Click Build Now

---

## Jenkinsfile Commands

Build Stage:

echo "Building Application"

Test Stage:

echo "Testing Application"

Deploy Stage:

echo "Deployment Successful"

---

## Pipeline Verification

Build Now

Console Output

Stage View

Workspace

---

## Additional Commits

git add Jenkinsfile

git commit -m "Added Jenkins Pipeline"

git push

git add .

git commit -m "Added screenshots and reports"

git push

---

## Final Verification

git log --oneline

git status

git branch

git remote -v
