# 1/ Initial information
### git config --global user.name "xxx xxx"
### git config --global user.email "xxx@gmail.com"

# 2/ Check information
### git config --list

# 3/ Create local repository
### git init code_folder_git

# 4/ Copy current project to code_folder_git

# 5/ Add code and commit
### git add . 
### git commit -m "First Commit"

# 6/ Create repository in github

# 7/ Push to server
### git remote add origin https://github.com/phien-ntace/how_to_use_git.git
### git push -u origin master (origin: default name of repository on your PC)

# 8/ Push any change after
### git add . (Commit all changed files)
### git push origin master

# 9/ Delete a file
### git rm $file_name
### git push origin master

# 10/ Get log and status
### git log
### git status

# 11/ Update code
### git pull or git fetch + git merge

# 12/ Branch
### Create branch: git branch branch_name
### Check current branch: git branch
### Switch to branch name: git checkout branch_name
### Push branch first time: git push --set-upstream branch_name
### Merge branch to master: git checkout master + git merge branch_name
