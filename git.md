# GIT
## its a version control system for storing data
git is helpful lto minimize the possibilty of irreversible damage to files
we use shortcut we use to save the modifing file and push to the cloud (github) the shortcut we use was : commited , add , push by these 
Git is a DVCS that stores data in a file system made up of snapshots.
##### Each time you save a changed version of your project 
- called commit
- Git creates a snapshot of the file and stores a reference to it.
##### If the file has not changed, Git only stores a reference to the already-stored identical version of it.
## Getting Started
#### Download Git
In order to use Git, your computer must have it available. If you already have Git on your computer, you should make sure you have the latest version.
#Git can be installed in three ways:

- Install as a package
- Install via another installer
- Download and compile the source code.
#### Default Text Editor
Without configuration of a default text editor, Git will use the system’s default editor–most likely Vim. To configure a different text editor, such as Emacs, type the following into your Terminal or Command Line:
#### Check Settings
To check settings, use the git config --list command.
#### Cloning
You can also create a copy of an existing Git repository from a particular server by using the clone command with a repository’s URL:
$ git clone https://github.com/test
#### Check File Status
To determine the state of files, utilize the git status command:
$ git status
#### Committing a File
After staging one or multiple files, you should commit the changes and record what you did within the commit message:
$ git commit -m “made change x,y,z”
