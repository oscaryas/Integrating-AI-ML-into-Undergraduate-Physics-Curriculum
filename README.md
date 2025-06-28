# Hello-World
This is will be your hello world of version control commands and Github repositories. 

What is version control?

Version control is a method/tool to track changes to files over time. It lets you go back to previous versions, collaborate with others, and avoid losing work. When word documents saves your work, that is a form of version control that is occuring in the background. 


Github vs Git:
Git is the tool that tracks your changes locally, while GitHub is a cloud-based platform that hosts Git repositories and enables collaboration with others. So git the actual language that saves changes, GitHub saves changes to the internet. 

Step 0: Retrieving Files
When you see a new Git repository on GitHub, you need a way to **copy it to your local machine**. (Desktop)
Since I have the "master" copy, the typical practice is to first **fork** the repository:

In order to retrieve files, you will have to use the command:
git clone git_repo_link

git clone git_repo_link adds the files locally to your machine. 

!](images/diagram.png)

Step 1: Editing Files
Go and write nonsense into that text file. 
Once you cloned your repository, you will want to update your own timeline that stored on Github. 

In order to do that you must first update the timeline on your Desktop. 
So:
git add folder_name 
git commit -m "What you edited"

In order to change the timeline on Github you:
git push folder. 

Git add places all edits into a temporary space, before making adding it to your timeline. 
Git commit adds all the edits you've stored into that temporary space to the timeline that is represented by a node. 
You can add as many changes you want, but you're edits aren't saved yet. The commit saves all edits in the temp space onto the timeline. 

Git push adds the latest version of your your edits to the remote or internet repository. Basically updates your code on the web. 

Step 2:
Once you have succesfully done this I want you to find a classmate, and get them to add you as a contributor to their git repository. 
You will then git pull their 

