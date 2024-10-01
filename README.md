# Azure-DevOps-Services
cron1
Self-Hosted Agent Why?
So, there's lots of reasons why you would want to host
your own build agents.
And one is because maybe you have an already pre-existing
build agent like a Jenkins server
or something on premise that you're using.
Another reason would be to lock down
the rights to use those build agents.
Maybe you have security parameters that you need to use
and maybe it's behind a firewall,
(which we'll discuss in the next lesson)
but maybe there are certain access permissions.
Another reason could be that you're using
Team Foundation Server and you need to have your CI server
centralized in that kind of non-distributed way
and have everything under the control
of that Team Foundation Server.

Tracking Changes from GitHub in Azure Boards

Additional Resources
With the provided credentials, log in to the Azure Portal and create a new Azure DevOps organization. Proceed to create a new project or import an existing project (with work items pre-populated) using the Demo Generator.

In order to synchronize your GitHub account with Azure DevOps, you will create and authenticate a connection in the project settings. You may use your existing GitHub account or create a new one for free.

Once you have connected your GitHub account to an existing project, create a change to the code, create a new branch for the commit, create a pull request, and then merge into the master branch. You should see all these changes automatically appear in the Kanban Board.

Note: Your commit messages must be in the following format: fixed AB#<issue number> (e.g., fixed AB#123).

Learning Objectives
0 of 5 completed


Create a New Azure DevOps Organization

Click All services in the left-hand menu, and select Azure DevOps.
Click the My Azure DevOps Organizations link (this will open a new tab).
Once the fields have auto-populated with the name, email, and location, click Continue.
Under Get started with Azure DevOps, click Create new organization.
If prompted to agree to the terms of service, click Continue.
Choose a name for your new DevOps organization (the default will suffice).
Choose the location Central US for the region to host your projects in, and click Create.
Use the Demo Generator to populate the Azure Board.
On the Demo Generator website, click Sign In, scroll to the bottom, and click Accept.
On the Create New Project screen, select the organization you just created in the previous steps from the dropdown menu.
Enter the project name "PartsUnlimited".
Click Choose template, choose PartsUnlimited from the pop-up menu, and click Select Template.
Click Create Project.

(Optional) Create a New GitHub Account for Free

In a new browser tab, navigate to https://github.com.
Click Sign up.
Create a new username, enter your email address, and create a new password.
Click Verify to verify your account, and click Next: Select a plan.
Under Choose a plan, select Choose Free.
On the Welcome to GitHub page, scroll down and select Skip this step.
GitHub has just sent you an email. Click the link inside the email to verify your email address. (Once you've clicked the link in the email, you are brought back to GitHub.com.)

Fork the PartsUnlimited Repo and Connect GitHub Account

Fork the PartsUnlimited repo to your GitHub account.
Open the Azure DevOps project you created in the first task.
Click Project settings in the lower left corner.
Select GitHub connections and then Connect your GitHub account.
Select Authorize AzureBoards when prompted. (This directs you to GitHub.com temporarily.)
Back in your project settings, select the PartsUnlimited forked repo and click Save in the bottom right corner.
Click Approve, Install, & Authorize when prompted. (This directs you to GitHub.com temporarily.)

Change the Code in GitHub and View Tracking Info Within the Work Item

Click Boards in the left-hand menu.
Click Boards as the sub-menu item, and select PartsUnlimited Team boards.
View the bug labeled Decline in orders noticed - Please Investigate immediately, and copy the issue number (needed for the following steps).
Go over to the repository you forked in the previous task (in GitHub).
Select the PartsUnlimited.Mobile.sln file from within the repository.
Click the pencil icon to edit the file.
Type in your changes to the file (e.g., add the comment "# Orders Change").
Scroll down and enter your commit message and paste in the issue number. (This must be in the format fixed AB#<issue number>).
Select Create a new branch for this commit and start a pull request, and click Propose file change.
Leave a comment in the pull request (e.g., "change orders"), and click Create pull request.
Click Merge pull request to merge this branch to the master branch, and click Confirm merge.
Go back to the Kanban board and view the changes, as they were automatically synced with the work item. Notice the issue has been moved across the board into the Done lane


Build Badge

<img width="403" alt="image" src="https://github.com/lellaaditya/Azure-DevOps-Services/assets/139613275/edaecf2c-f77f-417f-aedf-f06ec40351cd">

Copy  and paste in the github README.md
