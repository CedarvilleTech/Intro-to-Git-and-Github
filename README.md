# Introduction to Git and Github

## What is Git?

Git is a version control system that allows you to track changes in your code. 
It is a version control system, which means that it allows you track changes like code edits or bugs and then update your changes to a remote repository when you are ready.

## What is Github?

Github is a website that hosts your repositories or projects. It is a platform that allows you to collaborate with other developers and share your code with the world.

## Why use Git and Github?

- **Version Control**: Git allows you to track changes in your code.
- **Collaboration**: Github allows you to collaborate with other developers.
- **Portfolio**: Github is a great way to showcase your projects to potential employers.
- **Open Source**: Github is a great way to contribute to open source projects.

## How to use Git and Github?

1. **Install Git**: You can download Git from [here](https://git-scm.com/downloads).
   To check if Git is installed, open your terminal and type `git --version`.

2. **Create a Github account**: You can create a Github account [here](https://github.com/) if you don't have one.

Now that you have Git installed and a Github account, we can start using Git and Github,


## Terminology that you should know:

- **Directory**: A folder in your file system.
- **Terminal**: A text-based interface for text commands.
- **Command Line Interface (CLI)**: same as terminal but for a specific purpose mainly installing packages, running scripts, etc.
- **cd**: Change directory.
- **codeeditor**: A text editor that is used to write code.
- **Repository**: A folder that contains your project files.
- **Github**: A website that hosts your repositories.

## Basic Git Commands:

1. **git init**: Initializes a new Git repository.
2. **git add .**: Adds all the files in the directory to git.
3. **git commit -m "message"**: saves the changes made in Git.
4. **git push**: uploads the changes to the remote repository like Github.
5. **git pull**: downloads the changes from the remote repository to your local machine.
6. **git clone**: brings a repository from github to your local machine.

## Creating a new repository on Github:

1. Go to [Github](https://github.com/) and login.
2. Click on the `+` icon on the top right corner and select `New repository`.
3. Give your repository a name and click on `Create repository`.
4. Now you can add your code to the repository.


## Create a file in your repository:

1. Go to your repository on Github.
2. Click on `Add file` and select `Create new file`.
3. Give your file a name and add some code.
4. Click on `Commit changes` to save your file.

## Clone a repository:

1. Go to the repository on Github.
2. Click on the `Code` button and copy the URL.
3. Open your terminal and type `git clone <URL>`.
4. Now you have the repository on your local machine.
5. Whenever you clone you are on the main branch.

## Checking the status of the git repository:

1. In terminal type `git status`.
2. You will see the files that are staged, unstaged, and untracked.

## Adding files to git:

1. In terminal type `git add .` to add all the files to git.
2. In terminal type `git add <filename>` to add a specific file to git.

## Committing changes to git:

1. In terminal type `git commit -m "message"` to save the changes made in git.
2. The message should be a short description of the changes made.

## Pushing changes to Github:

1. To avoid entering the password each time, sign in vs code with your github account.
2. In terminal type `git push origin main` to upload the changes to the remote repository like Github.
3. If you are on a different branch, replace `main` with the branch name.

## Create a repository on your local machine:

1. In terminal type `git init` to initialize a new git repository.
2. You will see a `.git` folder in the directory.
3. To connect to a remote repository, you need to add a remote repository URL.
4. In terminal type `git remote add origin <URL>` to add a remote repository.
5. Now you can add your code to the repository.

## Create a new branch:

1. In terminal type `git branch <branchname>` to create a new branch.
2. In terminal type `git checkout <branchname>` to switch to the new branch.
3. Or just type `git checkout -b <branchname>` to create and switch to the new branch.
3. Now you can make changes to the new branch.

## Merge a branch:

1. Before merging, check the differences between the branches.
2. In terminal type `git diff <branchname>` to see the differences between the branches.
3. Instead of merging directly, you can create a pull request on Github.
4. Go to the repository on Github and click on `Pull requests`.
5. Click on `New pull request` and select the branches you want to merge.
6. Click on `Create pull request` and then `Merge pull request`.

## Pull changes from Github:

1. In terminal type `git pull origin main` to download the changes from the remote repository to your local machine.
2. If you are on a different branch, replace `main` with the branch name.

## Delete a branch:

1. In terminal type `git branch -d <branchname>` to delete the branch.

## Undo changes in git:

1. In terminal type `git reset` to unstage a file.
2. In terminal type `git reset HEAD~1` to undo the last commit. (HEAD is a pointer to the last commit).
3. To undo a specific commit, type `git reset <commitid>`. ( You can get the commit id from `git log` ).
4. In terminal type `git reset --hard <commitid>` to delete all the commits and changes after the commit id.


## Fork a repository:

1. Go to the repository on Github.
2. Click on the `Fork` button on the top right corner.
3. Now you have a copy of the repository in your Github account.
4. You can make changes to the repository and create a pull request to the original repository.



## Conclusion:

Git and Github are powerful tools that every developer should know. It allows you to track changes in your code, collaborate with other developers, and showcase your projects to the world. I hope this article helps you get started with Git and Github. Happy coding! 🚀

## References:

- [Git Documentation](https://git-scm.com/doc)
- [Github Documentation](https://docs.github.com/en)
- [Git and GitHub for Beginners - Crash Course](https://www.youtube.com/watch?v=RGOj5yH7evk&t=455s)
- [Github Copilot](https://copilot.github.com/)


---

The tutorial was prepared by [Daniel Dukundane](https://github.com/Daniel-Dukundane). If you have any questions or feedback, feel free to reach out to me on [LinkedIn](https://www.linkedin.com/in/duku-daniel/). Thank you for reading! 🙏

---
```
