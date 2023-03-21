# Section 2 Git and GitHub


# Project -> Repo -> Ignore -> Remote -> Push.

``People Rarely Incinerate Red Porcupine.``

**Ignore**

- To ignore certain files or directories in a Git repository, you can create a file called ".gitignore" in the root directory of the repository. 
- The ".gitignore" file specifies patterns for files and directories that should be excluded from version control. For example, you might want to ignore temporary files or files that contain sensitive information. 
- The ".gitignore" file is committed to the repository like any other file, and Git will automatically exclude the specified files and directories from version control.
- Only storing what needed to store. think of the files you want to ignore and not ignore.
- Assets that doesn't need to be track such as:images,clips,icons etc.

**Repo**

- Start tracking the changes from the project, means putting a folder within your project that is called .git


**Pushing**

- Sending project to the web with the HISTORY.
- Staging - is the next stage towards commiting.

**Setting Up Remote**

- To create a remote GitHub repository, you first need to sign up for a GitHub account if you don't already have one. Once you have an account, you can create a new repository by clicking the "New" button on the GitHub homepage or on the "Repositories" tab of your profile page.

- When creating a new repository, you'll be prompted to enter a name and description for the repository, specify whether it should be public or private, and select any additional options you want to enable, such as initializing the repository with a README file.

- Once you've created a remote GitHub repository, you can clone it to your local computer using the Git command line interface or a Git GUI tool. This will create a local copy of the repository on your computer that you can work on and synchronize with the remote repository on GitHub.

- To push changes from your local repository to the remote repository on GitHub, you can use the Git command line interface or a Git GUI tool to commit your changes and then push them to the remote repository. This will update the files in the remote repository and make them available to other developers who have access to the repository.


``add-on notes : ``

- GitHub is a web-based hosting service for Git repositories. It provides a centralized location where developers can store their code and collaborate with others.

- Github Limitation - 100mb single file limit. - you can't do lock asset.

- Bookmarks - are the things that open when you first thing you sourcetree. 

- important - dont mess with .git folder it can break thing. you can delete it to delete histories.