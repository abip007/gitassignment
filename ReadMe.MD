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
ssh-keygen -t ed25519 -C "email@gmail.com"
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

Task 4 

 I create hello.txt file in dev branch
 with command
 1. nano hello.txt with text Hello World from the dev branch!
 2. git add .
 3. git commit -m "Hello.txt added to Dev branch"
 4. git push -u origin dev

Task 5

i pull dev branch with command

1. git pull
2. change my hello.txt file
3. git add .
4. git commit -m "More Changes done in Dev Branch after Pull Request"
5. git  git push -u origin dev

Taks 5:

I now switch to main branch with command 

1. git checkout main
2. git merge dev

After that i found hello.txt in dev and main have same data


