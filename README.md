# git_command_practice
git command practice repository

first commit and connect with github by using SSH key on cli.
git add README.md
git commit -m 'commit message'
git push origin main

second commit and make branch and checkout to origin develop branch
git checkout -b develop
git add README.md
git commit -m 'commit message'
git push origin develop

third commit and merge to main branch from develop branch
git add README.md
git commit -m 'commit message'
git push origin develop
git checkout main
git merge develop

fourth commit and make new_develop_branch from main branch
git branch new_develop_branch main
git checkout new_develop_branch
change and save README.md 
git add README.md
git commit -m 'commit message'
git push origin new_develop_branch


