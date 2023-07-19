Basic GIT Commands
Here are some basic GIT commands:

git init will create a new local GIT repository. The following Git command will create a repository in the current directory:
git init
Alternatively, you can create a repository within a new directory by specifying the project name:
git init [project name]
git clone is used to copy a repository. If the repository lies on a remote server, use:
git clone username@host:/path/to/repository
Conversely, run the following basic command to copy a local repository:
git clone /path/to/repository
git add is used to add files to the staging area. For example, the basic Git following command will index the temp.txt file:
git add <temp.txt>
git commit will create a snapshot of the changes and save it to the git directory.
git commit –m “Message to go with the commit here”

