# Git Assignment - <okkycorp>
a. What is an issue?

An issue is like a to-do list system in a development, such as a list of taks that need to be completed. For example, a work that need to be completed, a bug that need to be fixed, or a new feature that need to be impemented. It is a system for the team working in a project to see all the tasks available, tasks being worked, tasks, completed, and etc. The system keeps track of the tasks assigned to each team member.

b. What is a pull request?

Pull request is like proposing your work for a review and if it's good, it can be merged to the main branch.

c. How do I open up a pull request?

Opening a full request:
1.) Commit all the changes in the local branch.
2.) Push the local branch to the remote repository
3.) On GitHub.com, go to the main repository and click on "Pull Requests" tab, then click on "New Pull Request" button
4.) Create a pull request to open a form to add title, description, etc to the pull request
5.) Write short sentences about the work being done, explaining the changes, and why it can be merged
6.) Submit the pull request by clicking on "Create Pull Request" button to submit



d. Give me a step by step guide on how to add someone to your repository.
1.) In my repository page on GitHub, under Settings tab, manage Access and click on Collaborators & Teams
2.) Add Collabolator, click on Add People or Add Teams
3.) Search and Invite, start typing the name of the person or team to invite
4.) Set permission such as a role to grant to the person or team
5.) Send the invitation

e. What is the difference between git and GitHub?

Git is a software installed locally which is a system for version control which keeps track of the changes in my code over time. It uses command line in a terminal and can also be accessed via GUI in Visual Studio Code. With Git, you can create different branches, manage versions, and merge changes.

GitHub is like a cloud service to upload your local git repository. It has useful features for collaboration such as issue tracking, pull requests, and documentations.


f. What does git diff do?
The command shows the difference between two versions in the repository. It can be used to keep track of the changes in the code or text documents in the repository.


g. What is the main branch?
Main branch is the production code base. To prevent any downtime due to error in code, etc, it is better to fork into own repository and work on the development there. Within fork, we can also create branches for different versions of the code. When the code is ready and committed in a fork, a pull request can be made for review before merging it into the main. 

h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?
No, we push the changes into our own branch. Then we can do pull request for code review before merging it into main.