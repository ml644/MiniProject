# Explanation and Examples for usage use on Git commands and terminology

## Basic Git Commands to Know

**Repository** - A directory or storage space where your projects can live. Sometimes GitHub users shorten this to “repo.” It can be local to a folder on your computer, or it can be a storage space on GitHub or another online host. You can keep code files, text files, image files, you name it, inside a repository.

**Clone** - When you create a repository on GitHub, it exists as a remote repository. You can clone your repository to create a local copy on your computer and sync between the two locations.

**Fork** - A fork is a copy of a repository. Forking a repository allows you to freely experiment with changes without affecting the original project.

**Branch** -  Working with multiple collaborators and want to make changes on your own? This command will let you build a new branch, or timeline of commits, of changes and file additions that are completely your own. Your title goes after the command. If you wanted a new branch called “cats,” you’d type git branch cats.

**Commit** - Git’s most important command. After you make any sort of change, you input this in order to take a “snapshot” of the repository. Usually it goes git commit -m “Message here.” The -m indicates that the following section of the command should be read as a message.

**Merge** - When you’re done working on a branch, you can merge your changes back to the master branch, which is visible to all collaborators. git merge cats would take all the changes you made to the “cats” branch and add them to the master.

**Checkout** - Literally allows you to “check out” a repository that you are not currently inside. This is a navigational command that lets you move to the repository you want to check. You can use this command as git checkout master to look at the master branch, or git checkout cats to look at another branch.

**Push** - If you’re working on your local computer, and want your commits to be visible online on GitHub as well, you “push” the changes up to GitHub with this command.

**Pull** - If you’re working on your local computer and want the most up-to-date version of your repository to work with, you “pull” the changes down from GitHub with this command.

**Remote** - Use the git remote rm command to remove a remote URL from your repository.

**Status** - Check the status of your repository. See which files are inside it, which changes still need to be committed, and which branch of the repository you’re currently working on.


 [Return to README](https://github.com/ml644/MiniProject/blob/master/README.md)

<img src="https://github.com/ml644/MiniProject/blob/master/linux.png" width="48">

