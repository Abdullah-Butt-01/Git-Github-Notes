# Day 04 - Merge Conflicts & Recovery

## Objective

Understanding what merge conflicts are and how to resolve them

## Commands Practiced

* 

## what I did

* Created a branch "branch-A", created a file "story.txt", edited it and commited to git
* Switched back to master branch
* Created another bracnh "branch-B", creted same named file "story.txt", edited with different text, and commited to git
* Merged the branch-A to master branch successfully
* When merging branch-B, conflict occured
* Edited the file, committed again to resolve conflict

## Problems Faced

* Confised when branch-B or master branch didnt contained the file "story.txt" when it is commited in branch-A

## How I fixed

* The branch-B was created from master branch, which is not already mergecd with branch-A, so the file didn't appear there

## Key Learnings
* Merge Conflict: Two different verisons of the same file, which one to choose
