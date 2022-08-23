# First Readme File 

## First edit from my local text editor!!!! 
 Now I realize the scare of git is sometimes way more than the complexity of using Git and Github repositories itself!!

## Some important Git commands.
1. clone : This command is used to bring a repository that is hosted somewhere to the likes of version control systems sych as github, gitlab, bitbucket etc into folder to a local machine.

2. add : This command is used to track all the files and changes in the particular git.

3. commit : Saves our files in the git.

4. push : Upload git command to remote repo like github, gitlab

5. pull : Download changes from remote repository to the local machine, opposite of push 

6. log : This git command is used to see the last git requests 


## How to push the files?
1. push origin <branch-name> : after committing the changes we use this command, whether in whi0ch branch we are pushing the           commits, here we are pushing it to "branch-name".

2. push -u origin <branch-name> or push --set-upstream origin <branch-name> : It sets default push branch, after this command in terminal we no longer need to specify the origin of repo. We can simply use the "git push" command to push our commits to "branch-name".


 ## How to create a new branch?
 A new branch is usually made to develop side features and not make them interfere with the original code so as to not break it from any error. There can be other use cases too. Some commands are :-

 1. checkout -b <branch-1> : It is used to create a new branch with name "branck-1" (ignore those brackets). 
 
 2. branch : It is used to show the developer in which branch the local machine connected to.
 
 3. checkout - <branch-name> : It is used to change to the "branch-name" branch. It works only if the branch has been created previously.  
 
 4. diff <branch-name> : It tells us the difference in entries between the branch we are in presently to the "branch-name".