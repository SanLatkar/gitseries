**Consists of All tasks:**
Hello everyone , I am **Saksham Garg** and currently pursuing my  Btech degree  in computer science from UPES,dehradun.


### Task 1 :
*1.What is git and GitHub?

*Git is a distributed version control tool and helps in merging different source code. From version control system I mean that it helps in recording and managing a project's source code and its past versions as well. It helps in keeping track of changes made in a source code and all this is done with the help of repositories  which it maintains and managing them. It is a open source tool and is completely self sufficient, installed on our local system rather than in the cloud.

*Github is a cloud-based hosting service used to host open source projects and thus help in bringing team together. It is used to manage Git-repositories.

*2.Why GitHub is so popular in most of the project?

*Github is so popular in most of the projects because:
*(A) It provides secure cloud storage for source code
*(B) It has collaboration feature which helps in bringing team together.
*(C)It supports all programming languages.
*(D)It came up with a Model-view-presenter.

*3.Whay are the other platforms similar to Github?

*(A) SorceForge
*(B) GitLab
*(C)Phabricator




### TASK 2

*(A) How git workflow works?
*There is one Central repository. Any developer who wants to make any changes clone that repository and make changes locally using commit command. Then pushes it to the central repository so that any other developer wanting to make any change can pull and use in their work.

*(B) What're the different stages of a git project as commit, add? 
*Git Workflow consist of the four fundamental elements: 
•	Workspace(also known as Working Directory) and if we consider a file, it can have 3 states:
 *(a)Committed : meaning latest changes in the data is stored in local repo.
 *(b)Modified: means the changes are done but are not securely stored or will not be reflected in local repository.
 *(c)Staged: meaning file is part of index element.

•	Index(also known as Stage)
•	Local Repository(also known as Head)
•	Remote Repository
  
*CLONE COMMAND: If we are gaining access to a remote repository then we need to clone it by following it by URL using git clone command which will create a local cpopy of repository in our workspace.
*ADD COMMAND: This command will add the file in the workspace in the index stage and thus we call this file as staged file.
*COMMIT COMMAND:  This command will commit all files that are staged with their changes and are safely stored.
               
*We can perform these add and commit commands in a single defined command as commit -a which helps in commiting all files at once if they are part of repository and already known.
*PUSH COMMAND: It pushes the changes that are in the local repository to the remote repository and anyonce having access to this remote repo can see the changes.
 
*For opposite flow we have following commands:

*FETCH COMMAND: Used to get files from the remote repository to local repository.
*MERGE CAMMAND: It get changes from local repo and get them to workspace.
*DIFF COMMAND: Used to tell the difference between files which are in workspace and ones which are stagged for commit.

*(c) Is it possible to do a git commit before git add . if you have made any changes? Explain why?
*No ,it is not possible because first according to the workflow, we first have to add the file to the staging area and then we can commit changes in the respective file in local repository.

 *(d) Why is git diff used?
*This command is used to check the difference or changes made on a files in the workspace.

 *(e) Can we leave the commit message as blank?
*Yes, it  is seen as a vvalid request and we can do it by using following command :
*git commit -a --allow-empty-message -m ""

My Github Repository link is:
https://github.com/sgarg-10/Virtual_Intern

Regards
Saksham Garg(UPES)



### TASK 3

Fork in git means making a personal copy of someone else's project or repository which helps us to modify and make changes in it without affecting the orignal project.It acts as a bridge between orignal repo and the copy we made.
Clone is used to create  a local copy of the remote repository.This process helps us to edit and modify files locally.


b. What are branches in Github?
A branch in github can be said as individual project or files inside a git repository. These files are not a part of main default branch of a git repository known as "master branch" which keeps the default commits we make.
For making a link of these projects, we can merge this branch to the master branch.

c. What is PR?
Pr, Pull Request can be seen as informimg others about the changes you have made in a particular project of a particular branch.
Once we make a pull request, we are requesting other developer to review the changes we have made and if approved, they can merge our project into the master branch.


d. Can we delete the master branch if not Why?
Yes we can delete the master branch but for this we need to make a new branch and instead of master branch as default one, we need to make newly created branch as the default one.


e. How can we delete a branch? 
git branch -d name of the branch.he -d option will delete the branch only if it has already been pushed and merged with the remote branch. Use -D instead if you want to force the branch to be deleted, even if it hasn't been pushed or merged yet. The branch is now deleted locally.


LINKS FOR PR:

https://github.com/deepak2431/gitseries/pull/8

https://github.com/deepak2431/gitseries/pull/11



Regards
Saksham Garg
