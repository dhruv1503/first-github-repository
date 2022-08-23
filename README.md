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

 1. checkout -b <branch-1> : It is used to create a new branch with name "branch-1" (ignore those brackets). 
 
 2. branch : It is used to show the developer in which branch the local machine connected to.
 
 3. checkout - <branch-name> : It is used to change to the "branch-name" branch. It works only if the branch has been created previously.  
 
 4. diff <branch-name> : It tells us the difference in entries between the branch we are in presently to the "branch-name".

 ## How to merge the branch difference?
 We shall arrive at a situation where we want to add our final changes from branch to the main branch in the repo. Let's figure out how to merge our changes to main branch of repo

 1. As soon as we push our changes to Github regarding the sub branch (here, branch-name) our github website notifies us of some git push made to the sub branch and advices us to pull it to merge via a button. Click that button (green button at the time of creating the file).

 2. Add some comments when it asks and if you want or proceed anyway.

 3. If you are on your own git and are satisfied with changes, click on merge. 
 
 If you are on collaboration work you might not be able to do that directly, the participants, contributors and authors of that repo might evaluate your commits, and/or add comments to changes, if any. When you resolve those changes and commit again, then the merge may proceed. 

## How to pull the merged main branch?
After merge, in your local machine you might not be able to see changes in main branch, after merging. Thats because the changes have been made on github and git and not on your local machine. In order to reflect those changes in local machine. The command is as follows.

pull origin main : Main being the branch where merge has been made.

 ## How to delete a branch?
 After we merge our "branch-name" with "main" branch we shall no longer require the need of "branch-name", so in order to delete the branch our command shall be

 branch -d <branch-name> : This will delete the branch named as "branch-name".

 ## Topics for future 
 1. Merge Conflicts
 2. How to undo out commits and add commands?
 3. Forking in Git


 I'm learning these commands from www.freecodecamp.org and their youtube video link is https://www.youtube.com/watch?v=RGOj5yH7evk. If you feel don't want to spend around 1 hour watching the video and making notes and side by side. You can always refer this README. Thanks  



