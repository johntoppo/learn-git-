# learn-git-
Hello guys  this is john now I am going to tell you how to use git on your windows os or linux os
I am going to tell you very simple way to learn git commands and use github in your computer
so let's start


<h1> there is some basic step you have to follow </h1>

--> creat Account in github or bitbucket

-->create new reposetery 

--> and clone to your computer

git clone <server link>
  
example--> git clone git@github.com:johntoppo/python.git  

on windows you have to install first git softwart and run git bash on your system 

after that you need to genrate ssh key 

command --> ssh-keygen

it will genrate one key 
rsh_pub_ky
it is very imortant to keep safe this key. this is for security reason

copy you ssh key and go to you github profile > setting > ssh

there is some option like name 
 and paste you ssh key there
 
this is the process of connecting directly github profile to  your computer

now let's start the git command for uploading your file in github repsoetry

 
git init for inintalizing the .git folder no need to use

run this command once in your terminal 

git config --globla user.name "john"

git config --globla user.email example@gmail.com

git remote add origin git@github.com:johntoppo/python.git

if some remote link already existe there you have to remove that link first
 
git remote rm origin

now then again run 

git remote add origin git@github.com:johntoppo/python.git

now you are sucessfully connect to your repository

after that 

 git add .       --> for adding your file in you rep
 
 git commit -m "for testing"
 
 git status ---> you can check your file status
 
 now there are two method to push your file in your repo
 
first 

git push origin master


second

if your push command gives you some error then you have to apply 

git pull   ---> first

then

git push origin master

that's it
conguratulation now you successfully uploaded your file in github repo

<h1> happy coding</h1>
thank's


 
 





