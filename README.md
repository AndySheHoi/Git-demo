# Gitdemo

Simple Git Cheat Sheet



# show the git version
git --version

# initialized empty git repository(.git) under current folder
git init

# config username and email
git config --global user.name 'Your Name'
git config --global user.email 'Your Email'

# check all files status (stage / unstage)
git status

# add the file to stage
git add filename
git add *.html (add all html files to stage)
git add . (add all files to stage)

# remove the file from stage
git rm --cached filename

# commit 
git commit -m 'message'

# create .gitignore (Put filenames which you want to be ignored by git into the .gitignore file)
touch .gitignore

# show all your branches
git branch

# create a new branch
git branch branchname

# switch to the branch
git checkout branchname

# delete a branch
git branch -d branchname

# merge all files from the source branch to your current branch
git merge srcbranch -m 'message'

# show all your remote
git remote

# add a remote
git remote add origin HTTPS

# delete a remote
git remote remove origin

# push files from local to remote
git push -u origin remotebranchname

# pull(fetch + merge) from remote, do that if you cannot push 
git pull --rebase origin master

# clone from HTTPS
git clone HTTPS
