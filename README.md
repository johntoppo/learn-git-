# learn-git-
Hello guys  this is john now I am going to tell you how to use git on your windows os or linux os
I am going to tell you very simple way to learn git commands and use github in your computer
so let's start


<h1> there is some basic step you have to follow </h1>

--> creat Account in github or bitbucket

-->create new reposetery 

--> and clone to your computer

<h3>git clone <server link>
  
example--> git clone git@github.com:johntoppo/python.git  
</h3>
on windows you have to install first git software and run git bash on your system 

after that you need to genrate ssh key 

command --> <h3>ssh-keygen </h3>

it will genrate one key 
rsh_pub_ky
it is very imortant to keep safe this key. this is for security reason

<h3>copy you ssh key and go to you github profile > setting > ssh </h3>

there is some option like name 
 and paste you ssh key there
 
this is the process of connecting directly github profile to  your computer

now let's start the git command for uploading your file in github repsoetry

 
git init for inintalizing the .git folder no need to use

run this command once in your terminal 

<h3>git config --globla user.name "john" </h3>

<h3>git config --globla user.email example@gmail.com</h3>

<h3>git remote add origin git@github.com:johntoppo/python.git</h3>

if some remote link already existe there you have to remove that link first
 
<h3>git remote rm origin</h3>

now then again run 

<h3>git remote add origin git@github.com:johntoppo/python.git </h3>

now you are sucessfully connect to your repository

after that 

 <h3>git add .       --> for adding your file in you rep </h3>
 
 <h3>git commit -m "for testing" </h3>
 
 <h3>git status</h3> ---> you can check your file status
 
 now there are two method to push your file in your repo
 
first 

<h3>git push origin master</h3>


second

if your push command gives you some error then you have to apply 

<h3>git pull </h3>   ---> first

then

<h3>git push origin master</h3>

that's it
conguratulation now you successfully uploaded your file in github repo

<h1> happy coding</h1>
thank's


 
 





