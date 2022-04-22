# git-test

rm -rf .git
git status

git init

git add configs/*
git add dataset/*
git add models/*
git add runs/*
git add tools/*
git add utils/*
 git add requirements.txt
git add run_mp.sh
git add run_sp.sh

git commit -m 'initial commit'
git remote add origin https://github.com/inhoelee/pose-ode.git

git config --global user.email "inhoelee@snu.ac.kr"
git config --global user.name "inhoe"

git push origin main

# make branch
git branch develop

# switch
git switch develop

#From local to Remote repo.
git push -u origin develop
