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

fifth commit and make pull_request_branch from main branch
git branch pull_request_branch main
git checkout pull_request_branch
change and save README.md
git add README.md
git commit -m 'commit message'
git push origin pull_requset_branch
brew install gh
gh auth login
gh pr create --base main --head pull_request_branch --title "Add new feature" --body "This PR adds a new feature"

sixth commit and delete wrong commit
change README.md
git add README.md
git commit -m 'wrong commit'
git reset HEAD^
change README.md
git add README.md
git commit -m 'first wrong commit message'
change README.md
git add REAMDE.md
git commit -m 'second wrong commit message'
change README.md
git add README.md
git commit -m 'third wrong commit message'
git reset [second commit number]
git reset --hard [first commit number]
change README.md
git add README.md
git reset
git commit -am 'README.md add commit message'
git push origin main











