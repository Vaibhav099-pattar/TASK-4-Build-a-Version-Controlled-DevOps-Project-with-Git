 My GitHub Repository
Welcome to my GitHub project! 👋
 **Configuration**
 git config --global user.name 
 git config --global user.email
**To Initialize a Git Repository**
git init
**Add files to the staging area**
git add .
git add --all

**To get status **
git status

**Commit the changes**
git commit -m "Initial commit"
**Amend the last commit (e.g., to fix message or add changes)**
git commit --amend
**To Ignore Files with .gitignore**
touch .gitignore
**Check Unstaged Changes**
git diff
 **Check Staged Changes**
 git diff --staged
 **View commit log (one line per commit)**
git log --pretty=oneline
**View detailed commit changes**
git log -p
 **View commits since 1 day ago**
git log --since="1 day"
**File Reverting & Resetting**
 1.Discard changes in a file (revert to last committed version)
git checkout -- file2
2.Force checkout to discard all local changes
git checkout -f
**Branching & Merging**
git branch <branchname>
Merge source branch into target branch
# (First checkout target branch)
git checkout target
git merge source
**to untrack**
git restore --staged filename
**Git Alias**
git config --global alias.st status
**Add the remote repository**
git remote add origin <url>
**Push to GitHub**
git push -u origin master






 











 
