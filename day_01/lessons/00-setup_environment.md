<h1 align="center">Set up your environment</h1>
## Requirements
Before starting using the project you need to have the following requrirements:
```
- Github account
- Git
- python3 and pip
```
1. First you need to create an account on [Github.com](https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home)

2. Install Git and python

**Ubuntu :**
Open the terminal and run the following commands.
- Step 1 — Update and Upgrade
```bash
sudo apt update
sudo apt -y upgrade
```
- Step 2 — Install git
```bash
sudo apt install -y git 
```
- Step 3 — Install pip
```bash
sudo apt install -y python3-pip
```
- Step 4 — Install git
```bash
sudo apt install build-essential libssl-dev libffi-dev python3-dev
```
- Step 5 — Install venv
```bash
sudo apt install -y python3-venv
```
**Windows :**
- Step 1: Install git bash
`git bash` is program similar to the terminal in ubuntu, this program comes with git pre-installed and you can use nerby the same commands in linux.
1. Download `git bash` from [here](https://git-scm.com/download/win)
2. Double click the downloaded file.
3. Proceed with the installation.
- Step 2: Install python
1. Download `Python` from [here](https://www.python.org/ftp/python/3.10.1/python-3.10.1-amd64.exe)
2. Double click the downloaded file.
3. Proceed with the installation.

## Get started
After installing the requirements, now we can start the work, this instructions are the same for both systems `Windows` and `Ubuntu`.
1. Config your git:
open the terminal (or git bash for windows user) and run the following commands.
```
git config --global user.name "your_username"
git config --global user.email "your_email"
```
*Note don't forget to replace `your_username` and `your_email` with your information.*

2. Get your copie of the python for finance project.
- Now after you have your own github, you need to do a fork for this project (fork is copying a project to your projects)
- In the top right of this page press the button `fork` to do a fork for this project.
- Now you have your own copie of the project which is by the way linked by the original project.

*Note programmers call a project in github repository so for now we will use repo term as an alias for repository which is a project stored in github website*

3. clone the repo:
go to your repositories and open the python for finance repo, click on the code button (in green color), copie the link, and open your terminal, then 
- change the working directory to Desktop by runing:
```bash
cd Desktop
```
*Note if your system is in french you will need to replace Desktop with Bureau*
- Clone the project (replace <username> with your username without `<>`)
```bash
git clone https://github.com/<username>/Python_For_Finance.git
```
- Cd into the project directory:
```bash
cd Python_For_Finance
```
4. Now let's installed the requirement packages.
- Create a virtual environment
```shell
python3 -m venv main_env
```
- Activate the virtual environment
```shell
source main_env/bin/activate
```
- Install packages
```bash
pip install -r requirements.txt
```
5. Congratulation you finish all the steps, and you can start now coding.
- run the below command for opening the `jupyter notebook`
```
jupyter notebook .
```
- now in your browser open the url `http://127.0.0.1:8888/`.
>   And voila your done

## What's next
Now you have all things works great, you can work on jupyter notebook read the lessons and solve the assignments.
For grading your assignments you need to publish your code to github so we can see your solutions.

### How to publish your solutions:
We are using git which is a program for tracking your changes and can be used with github to publish your code.
#### What is Git?
Git is a popular version control system. It was created by Linus Torvalds in 2005, and has been maintained by Junio Hamano since then.

- It is used for:
    - Tracking code changes
    - Tracking who made changes
    - Coding collaboration
#### What does Git do?
- Manage projects with Repositories
- Clone a project to work on a local copy
- Control and track changes with Staging and Committing
- Branch and Merge to allow for work on different parts and - versions of a project
- Pull the latest version of the project to a local copy
- Push local updates to the main project

#### Working with Git
Each time you add a changes to your files inside the repo cloned, you need to add and commit the changes finaly push the changes, what does this mean, let's understand that together:

- **git status**
    - The `git status` command tells the current state of the repository.

- **git add**
    - `Add` command is used after checking the status of the files, to add those files to the staging area.
    - Before running the commit command, "git add" is used to add any new or modified files. 
- **git commit**
    - The `commit` command makes sure that the changes are saved to the local repository.
    - The command "git commit –m <message>" allows you to describe everyone and help them understand what has happened.
- **git push**
    - The command `git push` is used to transfer the commits or pushing the content from the local repository to the remote repository.
    - The command is used after a local repository has been modified, and the modifications are to be shared with the remote team members.

## Additional resources
- for more about git check this [link](https://www.w3schools.com/git/) 
- For more about linux commands check this [link](https://cheatography.com/davechild/cheat-sheets/linux-command-line/) 
