# Day 01 - Git Basics

## Objective

Learn what Git is, initiating git and basic commands

## Commands Practiced

* git --version - Current version of git you're using
* git init - activates git inside a folder
* git status - what is happening inside a folder
* git add <file_name> - track this file
* git commit -m "My first commit" - git commit: save snapshot, >
* git log - timeline of changes 
	- git log --oneline

## what I did

* Created folder /git/day-01
* Initiated git inside the folder
* Created a test.txt file and added it to git
* Added a commit
* Taken screesnshots and added to Screenshot folder

## Problems Faced

* When ran "git commit", author identity error occur

## How I fixed

* Setting name and email:
        - git config --global user.name"Abdullah_butt"
        - git config --global user.email"abd@example.com"
* Verifying name and email - git config --global --list

## Key Learnings
* Git: a system that track changes in oyur work so you don't lo>
* Git: Tool on your laptop, Github: Website to store Git projec>
* "ls -a" to check if git is working in a folder
* You have to add a file to git to make it tracked
