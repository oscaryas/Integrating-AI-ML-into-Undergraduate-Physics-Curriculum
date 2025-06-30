# Hello-World
This is will be your hello world of version control commands and Github repositories. 

What is version control?

Version control is a method/tool to track changes to files over time. It lets you go back to previous versions, collaborate with others, and avoid losing work. When word documents saves your work, that is a form of version control that is occuring in the background. 

Github vs Git:
Git is the tool that tracks your changes locally, while GitHub is a cloud-based platform that hosts Git repositories and enables collaboration with others. So git the actual language that saves changes, GitHub saves changes to the internet. 

Step 0: Setting up and forking. 
1. Set up an Github account
2. Make sure you are logged into the Github account. You should see a button that says Fork in the top-right corner of the page. Click this button to create a fork of this repository, which will be your own copy of the codebase to edit as you please. In the new page that comes up, confirm that you want to create the fork and your own Hello-World repository will be created on GitHub!
3. Note: There is a checkbox for "Copy the main branch only", for this lab this doesn't matter, but in a future lab or for your own project, you may take a second to think if you also want to copy the other branches.

4. Now that you have your own fork of this repository, close this page, go to your fork, and continue with the next instructions.

Step 1: Retrieving Files
After you have forked a new Git Repository on Github, you need a way to **copy it to your local machine**. (Desktop)
You will see the link after clicking the green colored button called "Code"
Since I have the "master" copy, the typical practice is to first **fork** the repository:
In order to retrieve files from Github, you will have to use this command:

git clone git_repo_link

git clone repo_link adds the files locally to your machine. 

![Diagram of model architecture](Images/git clone.png)

Step 2: Editing Files:
Locate the cloned folder. The clone folder should be called Hello-World. You can also tell the directory or current folder you are in by using the command "cd" in the terminal. 
Once you have located the cloned folder, go finish the exercises. 

Once you finish, you will go on to the next step. 

Step 3:
So you've edited the file. You now want to save your changes and upload those changes to Github. 
How do you do that?
In order to do that you must first update the timeline on your Desktop. 

So:
git add folder_name 
git commit -m "What you edited"

In order to change the timeline on Github you:
git push folder_name. 

Git add places all edits into a temporary space, before making adding it to your timeline. 
Git commit adds all the edits you've stored into that temporary space to the timeline that is represented by a node. 
You can add as many changes you want, but you're edits aren't saved yet. The commit saves all edits in the temp space onto the timeline. 

Git push adds the latest version of your your edits to the remote repository. Basically updates your code on the web. 








Step 4:
Once you have succesfully done this I want you to find a classmate, and get them to add you as a contributor to their git repository. 
You will then git pull their 

