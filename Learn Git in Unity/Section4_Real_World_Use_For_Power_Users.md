# Section 4 Real World Use For Power User

**Things to consider when setting up github**

- You and your co-worker's profile.
- Your prospects and customers experience.
- Organization / repository structure.
- Visual appeal / consistency.

**Force Push**

- force push should be used with caution and only in certain situations, such as undoing mistakes or making changes to a personal branch. When working with others, it's best to avoid force pushing altogether and use Git's standard workflows to collaborate and review changes.

**Contributing** to a project can be a great way to improve your skills, gain experience, and make a positive impact on a community. 

**Single file tracking system** is a method of organizing and managing documents or files by assigning a unique identification number or barcode to each individual file. This allows for easy tracking and retrieval of files when needed.

**Blame** is a command that displays the revision history of a file, and annotates each line of the file with the commit hash, author, and date of the last change made to that line.

**Market Place** where you can get extentions and add ons in github.

**Explore** lets you explore repositories.

**Git Large File Storage (LFS)** is an extension of Git that allows you to version large files in your Git repositories.

- Allows you to store 100mb above files

**Git Large File Storage Setup**

- Install Git LFS: First, you need to install Git LFS on your local machine. You can download it from the Git LFS website.

- Initialize Git LFS: Once Git LFS is installed, you need to initialize it in your Git repository. Navigate to your repository's root directory and run the following command:

        ``git lfs install``


**Git on Terminal**

- You can't do on GUI

- You can't see things insertion and deletion

**COMMANDS**

    $git status  :: list which files are staged, unstaged, and untracked
    $git commit -m "message" :: commits on the repo with the message using terminal
    $git diff "Commit Sha" --stat *"name of file you only want to see" :: to check Diff when Refactoring codes
    $git lfs migrate :: to push 100mb files on git hub.