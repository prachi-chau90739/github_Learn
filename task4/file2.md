# "QUESTION  & ANSWERS"
Hello Everyone,
My name is Prachi Chauhan and I'm persuing my bachelor in Technology degree from DIT University in Computer Science.  
## Task 1
 
Ques1. What is git and github? 
Ans1. Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.
Let me break it down and explain the wording:

Control System: This basically means that Git is a content tracker. So Git can be used to store content — it is mostly used to store code due to the other features it provides.

Version Control System:The code which is stored in Git keeps changing as more code is added. Also, many developers can add code in parallel. So Version Control System helps in handling this by maintaining a history of what changes have happened. 

Distributed Version Control System: Git has a remote repository which is stored in a server and a local repository which is stored in the computer of each developer. This means that the code is not just stored in a central server, but the full copy of the code is present in all the developers’ computers and the code is present in every developer’s computer. 

GitHub is a Git repository hosting service, but it adds many of its own features. While Git is a command line tool, GitHub provides a Web-based graphical interface. It also provides access control and several collaboration features, such as a wikis and basic task management tools for every project.

Ques2. Why GitHub is so popular and used in most of the projects?
Ans2. GitHub is so popular and used in most of the projects because :
    • Largest shared    repository
    • Immensely Powerful Community
    • Separate public and private repositories
    • Secure Cloud Storage    
    • Easy Version Control
    • Can be accessed anytime and anywhere  

Ques3. What are the other platforms similar to GitHub?
Ans3. Bitbucket
      GitLab
      GitBucket
      Source Forge
      AWS CodeCommit
      
    
## Task 2
Q1 how does git workflow work ?
Ans1 
git workflow mainly contains:
1. workspace - when the project is under developement, modification or changes it is located in this working directory 
2. Staging area/index- when the project is added and is ready to be committed
3. local repository - used to make changes locally, i.e using local computers 
4. remote repository - it is an  online server .

Q2 What are the different stages of a git project as commit, add? 
Ans2
1. add - this command adds a change in the working directory to the staging area. It tells git that we want to include updates to a particular file in the next commit
  
2. commit - this command is used to save our changes to the local repository. We have to explicitly tell git which changes we want to include in a commit before running the "git commit" command. This means that a file won't be automatically included in the next commit just because it was changed
   
3. push - this command is used to upload local repository content to a remote repository. 
   
4. fetch - it fetches all the changes from the remote repository and stores it in a separate branch in our local repository
  
5. pull - this command is used to fetch and download content from a remote repository and immediately update the local repository to match that content

Q3 Is it possible to do a git commit before git add. If you have made any changes? Explain why? 
Ans3  No it's not possible as a file must be added and then must be committed which will give a hash(unique ID) to the file and if u made changes then again a new hash will be generated.

Q4. Why is git diff used? 
Ans4 It is used to find the difference between the changes made on a file.
 
Q5. Can we leave commit message as blank? 
Ans5yes we can leave the commit message as blank
 By using the command
git commit -a --allow-empty -message -m ""

My github repo link is: https://github.com/prachi-chau90739/github_Learn.git


## task3




A. What is meant by the term fork and clone?

 
Ans.FORK: 

A fork is a copy of a repository. Forking a repository allows you to freely experiment with changes without affecting the original project.

CLONE: 

Clone means to copy.
Cloning basically means you want to get a local copy of the code present in the repository. After cloning you can then do whatever changes you like in the code and then you can pull the changes back to the repositoru.



B. What are branches in github ?

 
Ans - Git branch is a feature in git used for separating a feature or part of code from you your master in order not to mess something in your main code like suppose you have a website as a project in git and you want to add a new feature to it so you do it by creating a new branch for it so your main code remain the same as it and once you complete it then you merge it with your master.



C. What is PR ?

Ans - A pull request is submitted when you’ve worked on some code from a particular branch and want to inform the others of the changes you’ve made. people can be assigned to review and subsequently approve the request before your changes can be incorporated into the branch.



D. Can we delete the master branch if not why


Ans - yes we can delete the master branch , but only after creating a new branch and set that branch as the default one.




E. How can we delete a branch ? 


Ans - DELETING A BRANCH

Delete a remote branch -

git push origin --delete <branch> 


Delete a local branch -
 
git branch -d <branch>

Link:
https://github.com/deepak2431/gitseries/pull/49