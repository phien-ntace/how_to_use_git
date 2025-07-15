# 1/ Initial information
#### git config --global user.name "xxx xxx" 
#### git config --global user.email "xxx@gmail.com"
 
# 2/ Check information
#### git config --list
 
# 3/ Create local repository
#### git init code_folder_git
 
# 4/ Copy current project to code_folder_git
 
# 5/ Add code and commit
#### git add .
#### git commit -m "First Commit"
 
# 6/ Create repository in github
 
# 7/ Push to server
#### git remote add origin https://github.com/phien-ntace/how_to_use_git.git
#### git push -u origin main`* (origin: default name of repository on your PC)
 
# 8/ Update code (safe team workflow)
### Step 1: Always update your local code before pushing
#### git pull --rebase origin main
 
### Step 2: Add, commit and push normally
#### git add .
#### git commit -m "Your changes"
#### git push origin main
 
#### If conflict happens during pull (both modified same file/line):
- Git will show CONFLICT and stop.
- You must open the file and resolve the conflict manually.
- After resolving:  
#### git add <conflicted_file>
#### git rebase --continue
#### git push origin main
 
# 9/ Delete a file
#### git rm $file_name
#### git push origin main
 
# 10/ Get log and status
#### git log
#### git status 
 
# 11/ Branch
#### Check current branch: git branch
#### Switch to branch name: git checkout branch_name

#### Create branch: git branch branch_name
#### Push branch first time: git push --set-upstream branch_name  
#### Merge branch to main: git checkout main + git merge branch_name
