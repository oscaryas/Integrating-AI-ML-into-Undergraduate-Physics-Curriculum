# Hello-World
This is will be your hello world of version control commands and Github repositories. 

What is version control?

Version control is a method/tool to track changes to files over time. It lets you go back to previous versions, collaborate with others, and avoid losing work. When word documents saves your work, that is a form of version control that is occuring in the background. 

Github vs Git:
Git is the tool that tracks your changes locally, while GitHub is a cloud-based platform that hosts Git repositories and enables collaboration with others. So git the actual language that saves changes, GitHub saves changes to the internet. 

Step 0 Setting up and Forking: 
  1. Set up an Github account
     
  3. Make sure you are logged into the Github account. You should see a button that says Fork in the top-right corner of the page. Click this button to create a fork of this repository, which will be your own copy of the codebase to edit as you please. In the new page that comes up, confirm that you want to create the fork and your own Hello-World repository will be created on GitHub!
     
  4. Note: There is a checkbox for "Copy the main branch only", for this lab this doesn't matter, but in a future lab or for your own project, you may take a second to think if you also want to copy the other branches.

  5. Now that you have your own fork of this repository, close this page, go to your fork, and continue with the next instructions.
  
  6. Now find a partner and agree upon which "fork" or github repository you will be updating. It doesn't really matter who's it is. 

Step 1 Adding Collaborators:

  1. On the agreed upon repository go to settings. (Should look something like the image below)
![Image Test](/Images/Collaborators.png)  

  2. Click on Access on sidebar and then click collaborators.
  
  3. Type the username of the collaborator and add to repository.
  
  4. The collaborator should then receive an email and accept invitation. 

Step 2: Retrieving Files
After you have forked a new Git Repository on Github, you need a way to **copy it to your local machine**. (Desktop)
You will see the link after clicking the green colored button called "Code"
In order to retrieve files from Github, you will have to use this command:

```bash
git clone git_repo_link
```

git clone repo_link adds the files locally to your machine.

![Image Test](/Images/git%20clone.png)

Step 3 Cloning Files:
Locate the cloned folder. The clone folder should be called Hello-World. 
Once you have located the cloned folder, go finish the exercises. 

Once you finish, you will go on to the next step. 

Step 4 Creating Your Own Branch: 
Since you have a local copy of the exercises, we don’t want to tamper with the main branch. Think of the main branch as the official timeline of the project — you don’t want to accidentally break it.

Instead, create and switch to your own branch by running:

```bash
git checkout -b your_name
```
This does two things at once:

a) Creates a new branch called your_name (you can replace this with your own name or a short description of what you’re working on).
b) Switches you onto that branch, so all future edits you make will only affect this branch.

Now you’re working on your own “timeline” of the project. When you’re ready, you can push this branch to GitHub for your collaborator to review and merge into the main branch.

Step 5:
READ ALL OF STEP 5 BEFORE YOU RUN TERMINAL COMMANDS

So you've edited the file. You now want to save your changes and upload those changes to Github. 
How do you do that?
In order to do that you must first update the branch on your Desktop. When I say branch you can think of a timeline of the versions you have. 

So:
```bash
git add folder_name 
git commit -m "What you edited"
```

In order to change the branch on Github you:
```bash
git push folder_name. 
```

![Image Test](/Images/gitadd.png)

Git add places all edits into a temporary space called the staging area, before making actually creating a save state to your branch. 
Git commit adds all the edits you've stored into that temporary space to the branch that is represented by a node. 

So in terms of Word Doc example, git add and git commit save the current version you have. 

![Image Test](/Images/git%20commit.png)

The difference between git add and git commit is that git add just adds to the temporary space. 
You can add as many changes you want, but you're edits aren't saved yet. The commit saves all edits in the temporary space onto the branch. 

Git push adds the latest version of your your edits to the remote repository (Github). Basically updates the web stored version of your code. 

So in terms of word doc, it would be like uploading the current version you have to OneDrive for example. 

Step 6 Merging to Main Branch:
![Image Test](/Images/Merging.png)

Go to the Github and you should see something similar to the image above. If you don't you should check if you are currently on the main branch or on your_name branch on github. 
You should then click Compare and Pull Request.

This will open up a page where you can:
  a) Compare the changes you made on your branch against the main branch.
  b) Add a short description of what you changed (this helps collaborators understand your edits).
  c) Submit the pull request.

After submitting, your collaborator can review the changes. Once everything looks good, the pull request can be merged into the main branch.



