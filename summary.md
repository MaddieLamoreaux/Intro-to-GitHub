KEY TERMS
Repository (Repo):
A reespitory is similar to a folder, and it is a storage space where you code and porject files are stored.
It can be either local (on your computer) or remote (hosted on a platform like GitHub).

Commit:
A commit helps to document your changes to the repository.
It includes the current contents of the index (staging area) along with a log message describing the modifications.

Local and Remote:
Git operates both locally (on your machine) and remotely (on a server or hosting service like GitHub).
You work with the local repository on your computer and push changes to the remote repository.

Pull, Push, or Fetch:
Pull: Retrieves changes from a remote repository and merges them into your local branch.
Push: Sends your local commits to the remote repository.
Fetch: Retrieves changes from the remote repository without merging them.

Branch:
A branch is a separate line of development within a repository.
It allows you to work on features or fixes independently.

Pull Request:
A pull request (PR) is a way to propose changes from one branch to another.
It’s commonly used for collaboration and code review.

KEY GIT COMMANDS
Initialization: Start a new Git repository using git init.
Staging Changes: Add files to the staging area for the next commit with git add <file_name>.
Committing Changes: Commit staged changes using git commit -m "Your commit message here".
Checking Repository Status: View the current status of the repository with git status.

Branch Operations:
Create a new branch with git branch <branch_name>.
Switch to a different branch using git checkout <branch_name>.
Merging Branches: Merge changes from one branch into another using git merge <source_branch>.
Pushing Changes to Remote Repository: Push local changes to a remote repository with git push origin <branch_name>.
Pulling Changes from Remote Repository: Fetch and merge changes from a remote repository using git pull origin <branch_name>.
Viewing Commit History: Check the commit history using git log.

Configuring Git: Set up user information:
Set username: git config --global user.name "Your Name".
Set email address: git config --global user.email "your@email.com".

SUMMARY
With Git a respositories, which can aslo be known as repos, work as a storage space for code and project files, 
wether they are located on a persons computer or on platforms such as GitHub. The modifications will be documented 
through commits. Together with an explanation of the changes made in the log message, the commits help with condensing
the contents of the current index. Users can manage repositories on their computers and synchronize changes with remote
servers with Git. Because of this Git's ability to be both local and remote the workflow of pulling pulls changes from 
the remote repository, and pushing pushes local commits to the remote counterpart is made possible. Also, branching offers
separate development paths for specific features or bug patches inside the repository. The pull requests help to provide
easier collaboration by the ability to smoothly combine different branches.

Important Git commands provide many different functions and can help with managing version control and 
traversing repositories. Some example of Git commands are: 'git init' to start a repository, 'git add' to stage 
changes, 'git commit' to commit changes, and 'git status' to examine repository status. In order to promote development
routes, branch operations use the formation of new branches, smooth transitions between them, and the merging of modifications.
Git provides simple commands like 'git push' to send local commits to a remote repository and 'git pull' to get and incorporate
changes from a remote source, which help synchronize local and remote repositories. By putting usernames and emails through the
'git config' command it can be used to help complete the configuration of Git and ensures proper credit and accountability.
