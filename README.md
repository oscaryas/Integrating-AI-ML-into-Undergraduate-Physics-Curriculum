# Hello-World
This is will be your hello world of version control commands and Github repositories. 

What is version control?

Version control is a method/tool to track changes to files over time. It lets you go back to previous versions, collaborate with others, and avoid losing work. When word documents saves your work, that is a form of version control that is occuring in the background. 

Github vs Git:
Git is the tool that tracks your changes locally, while GitHub is a cloud-based platform that hosts Git repositories and enables collaboration with others. So git the actual language that saves changes, GitHub saves changes to the internet. 

Step 0: Setting up and forking. 
  1. Set up an Github account
     
  3. Make sure you are logged into the Github account. You should see a button that says Fork in the top-right corner of the page. Click this button to create a fork of this repository, which will be your own copy of the codebase to edit as you please. In the new page that comes up, confirm that you want to create the fork and your own Hello-World repository will be created on GitHub!
     
  4. Note: There is a checkbox for "Copy the main branch only", for this lab this doesn't matter, but in a future lab or for your own project, you may take a second to think if you also want to copy the other branches.

  5. Now that you have your own fork of this repository, close this page, go to your fork, and continue with the next instructions.
  
  6. Now find a partner and agree upon which "fork" or github repository you will be updating. It doesn't really matter who's it is. 

Step 1: Adding Collaborators

  1. On the agreed upon repository go to settings. (Should look something like the image below)
![Image Test](/Images/Collaborators.png)  

  3. Click on Access on sidebar and then click collaborators.
  
  4. Type the username of the collaborator and add to repository.
  
  5.  The collaborator should then receive an email and accept invitation. 

Step 2: Retrieving Files
After you have forked a new Git Repository on Github, you need a way to **copy it to your local machine**. (Desktop)
You will see the link after clicking the green colored button called "Code"
In order to retrieve files from Github, you will have to use this command:

```bash
git clone git_repo_link
```

git clone repo_link adds the files locally to your machine.

![Image Test](/Images/git%20clone.png)

Step 4: Editing Files:
Locate the cloned folder. The clone folder should be called Hello-World. 
Once you have located the cloned folder, go finish the exercises. 

Once you finish, you will go on to the next step. 

Step 3:
READ ALL OF STEP 3 BEFORE YOU RUN TERMINAL COMMANDS

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

For best practices, you don't want to update to the master branch immediately. You might want to create a new branch, a temporary timeline, to test and see if the changes you've made are correct before updating the master branch. Since you and your classmate will eventually be updating the main branch, if one of you updates the main branch, the other has to 



For best practices you don't want to update to the master branch immediately. You might want to create a new branch, a temporary timeline, to test and see if the changes you've made are correct before updating the master branch. 

![Image Test](/Images/branching.png)



Step 4:
Once you have succesfully done this I want you to find a classmate, provide your github username, and get them to add you as a contributor to their git repository. 







