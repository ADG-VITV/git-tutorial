# Welcome to this git tutorial!

## Go through the following steps:

- ### Install Git

    - [Windows](https://git-scm.com/download/win)
    - [MAC](https://git-scm.com/download/mac)

- ### Open `cmd` on Windows or `Terminal` on Mac and use the following commands:

        git clone https://github.com/abhinav-lv/git-tutorial.git

    You'll see a folder named "git-tutorial". Go into this folder and open a terminal there. You've just cloned the repository into your local machine! Now before you make any changes, it's a good idea to make a different branch so that if you mess up any commits, your main branch won't be affected. Follow the steps below to create a new branch:

- ### Create a new branch
        git checkout -b branch_name

    The "branch_name" can be any name of your choice. To make it simple for this tutorial, keep the branch name as <b>your</b> first name. This will come in handy later when you'll be learning about pull requests.

- ### Make changes !
    Mess around, add new files, edit existing files, etc. But make sure you don't edit the ```readme.md``` file.

- ### Stage the new files for tracking.
    - Run the following command: 

        ```
        git status
        ```
    - You'll see that the files you've added / edited show up as "untracked" by git. To stage them, run this command:

        ```
        git add .
        ```
        This stages all the changed files for commit.

- ### Commit !
    - To commit your changes (make them permanent), you need to commit them. You can commit your change by running the command:

        ```
        git commit -m "any short descriptive message here"
        ``` 
    
    - Make sure to give a message in double quotation after the ```-m``` flag. This should be a short description of the changes you made in this commit.

- ### Push the changes to the remote repository
    - The changes that you've made are saved in your local repository (the one on your computer). To update the same changes in the remote version (the one on GitHub), you need to push those changes.

    - But since you guys are doing this for the first time, there's a bit of a setup involved. For any action that you perform from the terminal that interacts with a repository on GitHub, you'll first need to authenticate yourself.

    - You can try pushing your changes by typing:
        ```
        git push origin your_branch_name
        ```
        