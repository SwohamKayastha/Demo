# Demo
Learning Git and GitHub

## Subheader

Git
- git status
- git add
- git commit -m "Description" 
- git push
- git ...

Git add new repo locally:
- git remote add origin git@github.com:SwohamKayastha/Weather-API.git
- git branch -M main
- git push -u origin main

Git branch
- git branch
- git chekcout -b branch_name
- git branch
- git branch -d branch_name
- git push --set-upstream origin branch/reset

Git reset
- git reset file_name

Git branch remotely added
- git init
- git remote add origin <git-url>
- git add .
- git commit -m "Description"
- git push origin HEAD:<new_branch_name>

Git Merging remote branch and main
- git fetch origin
- git branch                            #to check the branches
- git checkout main
- git merge remote_branch (optional --allow-unrelated-histories -> vim opens)
- vim opens
- i -> INSERT
- Add any additional information in the commit message
- Esc -> exit insert mode
- :wq and Enter -> to save the commit message and exit Vim

Git accessing a branch
- git fetch
- git checkout <branch_name>
- git branch -a

Git accessing git-bash name and emails registered
- git config -l | grep user.name
- git config -l | grep user.email

Git changing git-bash name and emails registered
- git config --global user.name "user_name"
- git config --global user.email "user@example.com"
