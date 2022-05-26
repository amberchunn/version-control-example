# version-control-example

Version Control Crash Course Unity project. This project is a sandbox project to allow for practice using Git version control.

# Git Crash Course

### Steps for creating a Git repo & connecting to your local project repo

1. Got to GitHub and create a new Repo
   1. Be sure to add .gitignore file for Unity
   2. Copy git repo address
2. Run `git init` inside of local project's main folder
3. Run `git remote add origin <repo url>`
4. Run `git remote -v` to check if local repo is connected to remote repo

### Steps for adding Unity project & progress to GitHub version control

1. `git pull origin main` - Run the first time you pull remote repo down into your local branch
   `git pull` - Pull remote changes down to merge with your changes
2. `git status` - Optional, shows all modified files that have yet to be committed
3. `git add .` - Adds all modified files
   1. `git add <item>` - Optional, adds individual items
4. `git commit` - Commits your changes to the branch
5. `git push origin main` - First time pushing project to Git
   1. `git push` - Push project to Git
