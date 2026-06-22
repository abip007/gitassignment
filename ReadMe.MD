Git Assignment
I Created Readme.txt file and hello.txt file as local project
on Project 
Task 1

1. Git init (To initialize as git repo)
2.Git add .
3.git branch -M main
4 git commit - m " First Commit "

Task 2

I created gitassignment repo in github with public

1  git remote add origin git@github.com:abip007/gitassignment.git

Before push i need to generate key to get permission

i genereate ssh key with command 
ssh-keygen -t ed25519 -C "abip007@gmail.com"
then i get key with command 
cat ~/.ssh/id_ed25519.pub

i just added that ssh key in my account setting ssh key section

then i push to remote using below command
  git push -u origin main

Task 3 

I create dev branch with command

1. git branch dev
2. git branch
3. git checkout dev