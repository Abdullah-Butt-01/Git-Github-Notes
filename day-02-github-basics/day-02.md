# Day 02 - Github Basics

## Objective

Learn what Github is, how to push code to github

## Commands Practiced

* git clone url-https - cloning the repo
* git remote add origin url - connecting local rep to GitHub
* git remote -v - checking remote connection
* git push -u origin master: pushing to GitHub
	- after this, just use git push
* rm -rf .git - remove the git
* git add . - adding whole project to Git
* git config --global credential.helper store - save credentials	

## what I did

* Logged in onto my GitHub account and created a new repository "linux-notes"
* In the terminal, created a clone of repo to work on the local system.
* Linked with GitHub and checked if it is working

## Problems Faced

* When changing the git email from abd@example.com to my real email, it was giving an error invalid email.
* Embedded Git Repo Error: i had accidently initialized git inside the linux folder, which caused a nested repo
* Everytime I tried to push changes to Github, it asked for username and password(token)

## How I fixed

* The problem was not adding space between user.email and first double quote: 
	- git config --global user.email "---" (space between them)
	- alongside this, get to know about some commands:
		- git config --global --unset user.email
		- git config --global --unset-all user.email
* Removed the nested git (rm -rf .git)
* Used "git config --global credential.helper store" to save the last credentials

## Key Learnings
* Git: version control on your laptop, Github: online storage + collaboration
* GitHub is used for reviewing code, tracking work, collaborate, and audit changes
* Git actions are manual, not automatic
