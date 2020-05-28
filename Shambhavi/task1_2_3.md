### TASK1_2_3
**Task1**
1.*What are git and GitHub?*
Git is a distributed version control tool that can manage a development project's source code history.Git is a tool a developer installs locally on their computer.
It does not require the use of any external, cloud hosting service to function. 

GitHub is a cloud based platform built around the Git tool. GitHub is an online service that stores code pushed to it from computers running the Git tool.
GitHub is an online service to which developers who use Git can connect and upload or download resources.


2.*Why GitHub is so popular and used in most of the projects?*
GitHub is so popular and used in most of the projects because of the following reasons:
a)Open, clear communication.
b)Public APIs. These allowed others to build upon their work.
c)The right amount of functionality: repo, issue tracking, wiki, GitHub Pages.
d)It is very intuitive and user-friendly UI/UX.
e)GitHub managed to come up with a Model-view-presenter (MVP)


3.*What are the other platforms similar to GitHub?*
a)Bitbucket
b)GitLab
c)Beanstalk
d)SourceForge


**Task2**
a)*How git workflow works?*
The main idea behind the  Workflow is that all feature development  should take place in a dedicated branch instead of the master branch. This encapsulation makes it easy for various  developers to work on a particular feature without disturbing the main codebase. We have  one central repository. Each developer clones the repository and locally made changes in the code and commit it and then pushes  it to the central repository so that the  other developers can  pull and use in their work.
b)*What're the different stages of a git project as commit, add? *
Git Workflow consist of the following: 
•	Workspace(also known as Working Directory)
•	Index(also known as Stage)
•	Local Repository(also known as Head)
•	Remote Repository
  git clone is a Git command line utility which is used to target an existing repository and create a clone, or    copy of the target repository. 
Add command adds the file from working directory to the index .
Furthur if we need to commit it in local repository we use commit command .
Commit  –a command is used to simply commit and stage at once.
push command is used to push the changes  from local to remote repository.
fetch command is used to get  the file from remote to local repository.
merge command takes changes  from local repository to workspace.
pull command will collect the changes from the remote repository then will be taken into  local repository and further into workspace in one go. 
 c. *Is it possible to do a git commit before git add . if you have made any changes? Explain why?*
No ,it is not possible because first we add file to stage and then we undergo commit or save it into local repository.
 d. Why is git diff used?
This command is used to check the difference between the files in the stage and in the workspace.
 e. Can we leave the commit message as blank?
Yes we can do it by using the below command :
git commit -a --allow-empty-message -m ""

**TASK 3** 

A. What is meant by the term fork and clone?
Fork in git means making a personal copy of someone else's project or repository which helps us to modify and make changes in it without affecting the orignal project.It acts as a bridge between orignal repo and the copy we made.
Clone is used to create  a local copy of the remote repository.This process helps us to edit and modify files locally.


B. What are branches in Github?
A branch in github can be said as individual project or files inside a git repository. These files are not a part of main default branch of a git repository known as "master branch" which keeps the default commits we make.
For making a link of these projects, we can merge this branch to the master branch.

C. What is PR?
PR, Pull Request can be seen as informing others about the changes you have made in a particular project of a particular branch.
Once we make a pull request, we are requesting other developer to review the changes we have made and if approved, they can merge our project into the master branch.


D. Can we delete the master branch if not Why?
Yes we can delete the master branch but for this we need to make a new branch and instead of master branch as default one, we need to make newly created branch as the default one.


E. How can we delete a branch? 
git branch -d name of the branch. The -d option will delete the branch only if it has already been pushed and merged with the remote branch. Use -D instead if you want to force the branch to be deleted, even if it hasn't been pushed or merged yet. The branch is now deleted locally.



Link for PR:

https://github.com/deepak2431/gitseries/pull/57
https://github.com/deepak2431/gitseries/pull/60

Regards 
Shambhavi Pandey
