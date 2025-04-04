# Version-Control-with-Git

**COMPANY**: CODTECH IT SOLUTIONS

**NAME**: GOOLLA HITHA HARSHINI

**INTERN ID**: CT12QVZ

**DOMAIN**: DEVOPS

**DURATION**: 8 WEEKS

**MENTOR**: NEELA SANTHOSH

# DESCRIPTION OF THE TASK
**Objective**:
To demonstrate basic Git operations by creating a repository, using branches for feature development, merging changes, and reviewing commit history-- all done locally.

**Steps Followed**:

**1. Setup and Repository Initialization**

-Opened Git Bash and navigated to the desktop directory inside OneDrive.

-Created a new folder **Git-Project** and initialized it as a Git repository using **git init**.

**2. Initial Commit in Master Branch**

-Created a file **file1.txt** using Notepad and added some initial content.

-Staged the file using **git add file1.txt** and committed using **Initial commit - added file1.txt**

**3. Branch Creation and Feature Development**

-Created a new branch named **feature-branch** using **git branch feature-branch**.

-Switched to the feature branch using **git checkout feature-branch**.

-Edited **file1.txt** to add or modify content, then staged and committed the changes using **Feature branch update**

**4. Merging Back into Master**

-Switched back to the master branch using **git checkout master**.

-Merged changes from the feature branch using **git merge feature-branch**.

-Git performed a **fast-forward merge**, indicating there were no conflicts between branches.

**5. Cleanup and Commit History**

-Deleted the feature branch using **git branch -d feature-branch** after successful merging.

-Verified commit history using **git log --oneline**, showing both commits in order:

-Feature branch update

-Initial commit - added file1.txt


