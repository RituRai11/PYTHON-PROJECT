# PYTHON-PROJECT
this is a simple python script that prints "Hello, world!' when running

## way to do


# Git & Terminal Commands Used in This Repository

This file contains all the commands used to set up and manage this project.

---

## ** 1. Setting Up Git Repository**
### **Create a new GitHub repository (Manually on GitHub)**
1. Log in to GitHub and create a new public repository.
2. Copy the repository URL.

### **Clone the repository to your local machine**
```bash
git clone https://github.com/YOUR-USERNAME/python-project.git

- cd python-project

#Creating necessary files
New-Item script.py
notepad script.py
 

Adding the following script 
# This script prints a welcome message
def main():
    print("Hello, world! This is my Python script.")

if __name__ == "__main__":
    main()
    
# create .gitignore file 
New-Item .gitignore
notepad .gitignore

#ADD FOLLOWING
__pycache__/
*.pyc
*.pyo
.vscode/
.idea/
   THEN THE README FILE WHICH YOU ARE VEIWING



#WE HAVE TO CONFIGURE GIT BY 
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"

#Add all files to Git tracking
git add .
 
#CHANGES 
git commit -m "Added Python script, README, .gitignore, and command list"

#PUSH CHANGES 
git push origin main


#RUN PYTHON SCRIPT 
python script.py



#VERIFY FILES IN THE REPOSITORY
ls

