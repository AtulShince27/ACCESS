## Your Guide to Contributing to this project:

# 1. Cloning the Github Project :

 - Clone the project using the following command:
> ```shell
> git clone https://github.com/AtulShince27/ACCESS/
> ```

# 2. After making changes to the project , Creating a New Branch:

 - Create a new branch that stages and commits all your changes using the following command:

> ```shell
> git checkout -B "branchName"
> ```
 - Once the new branch is created, you will automatically be present in the new branch. To view and change your current branch use the following command:

> ```shell
> # Viewing current branch:
> git branch
> # Changing to another branch:
> git checkout <branchName>
> ```
 - On running the "git branch" command your current branch highlighted with a star in the terminal.

# 3. Staging and Commiting Changes: 

- Here are the commands you should use to add changes to the staging area and to make commits:

> ```shell
> # Staging Changes:
> git add <fileName>
> # Staging All Changes Made:
> git add .
> # Commiting changes:
> git commit -m "Your commit message."
> ```

# 4. Pushing changes to the origin branch: 

- Use this command once you've commited all the necessary changes:

> ```shell
> # Pushing Commits:
> git push origin <branchName>
> ```

# 5. Create a Pull Request for your branch on the Github page:

- Create a pull request and add a reviewer who can review all the changes and merge the pull request with the origin/master branch of the project.

# 6. Git Stash and When to use git stash: 

- The git stash is a way for you to save your current progress on whatever branch it is that you're currently working on. Use this command when you're trying to checkout and shift to another branch to work on something else. Git stash stores all your progress in a way that you can use this progress to push and merge with the original branch later.

> ```shell
> # Stashing changes:
> git status
> git stash
> # Checking out to another branch after stashing
> git checkout <branchName>
> # Bringing back the stashed changes back:
> git stash pop
> # You can now commit and push your changes!
> ```  

