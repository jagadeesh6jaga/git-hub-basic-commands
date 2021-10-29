# common camands in git 

1.git clone

2.git checkout

3.git branch

4.git status

5.git  add

6.git commit

7.git pull

8.git push

9.git merge

10.git fetch


git init:
---------
--> git init 
 it is used to create repository or re-initiate existing repo 
(make dir as git dir )



to unstage any file 
--------------------

 git rm --catched <filename>

to unstage all files at a time:
------------------------------

 git rm --catched *

  this is for new created files


general process :
---------------

git status .

### add files / new files create .

git add <filename>

### to add all files at a time 
git add --a 
### to commit files
git commit -m 'commit-msg'

### get recent code from repo 
git pull

### push the code into repo
  
git push origin master  or git push origin HEAD:main
 
  
git remote add <repo-url>  ===>first time only .

ex for first time : git remote add origin https://github.com/jagadeesh6jaga/gittest.git





  
  
  


commit :
--------------


git commit -m ' commit-msg'

Note :Git local repository will be available in our machine only .

Note  : when we execute commit command it will consider all the files which are in staging area .




restore :
---------

git restore --staged <filename>

this is for modified  files .




checkout :
------------


git checkout <branch-name>  : this is used to change branch 
