# Git

- Git is a [version control](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control) system that developers use all over the world
  it helps to use different versions of code and collaborate with other developers.
- It helps us compare changes made over time.
- It keeps the history of who made the change and when. 
- For more visit [Git documentation ](https://git-scm.com/book/en/v2/Getting-Started-What-is-Git%3F)

You can checkout my [blog](https://satyampsoni.hashnode.dev/version-control-system-simplified) on version control.

# Installing Git
   ### windows
   - Navigate to the latest Git for Windows installer and download the latest version.
   - Once the installer has started, follow the instructions as provided in the Git Setup wizard screen until the installation is complete.
   - Open the windows command prompt (or Git Bash if you selected not to use the standard Git Windows Command Prompt during the Git installation).
   - Type `git version` to verify Git was installed.
   
   ### MacOs
   
   - Navigate to the latest macOS Git Installer and download the latest version.
   - Once the installer has started, follow the instructions as provided until the installation is complete.
   - Open the command prompt "terminal" and type `git version` to verify Git was installed.
   
   ### Linux
   
   - Git packages are available using apt.
   - It's a good idea to make sure you're running the latest version. To do so, Navigate to your command prompt shell and run the following command to make sure everything is up-to-date: `sudo apt-get update`.
   - To install Git, run the following command: `sudo apt-get install git-all`.
   - Once the command output has completed, you can verify the installation by typing: `git version`.
 
 # Git workflow
 changed ---> staged area ----> commit
 Git workflow is divided into three parts modified staged and committed.
 1. Modified - You have changed the file
 2. Staged - Staged means you have marked the modified file its current version for snapshot
 3. committed - committed means that the data is safely stored in local database or snapshotted.
    

# Git commands 
1. `git  init`: Initializes the empty git repository(creates a .git folder inside the directory)
2. `git add file_name`: Adds the file or stages the file
3. `git add .` : Adds the whole file or stages the whole file
4. `git commit -m "Type your message": ` : Commits the file or takes a snapshot of the file.
5. `git log` : Tells you the commit history of the file.
6. `git reset "hashvalue"`: Removing the commits from the staging area Note: Hashvalue is of the below commit from you want to remove
7. `git stash` : sending the files to backstagee "we do it when we neither want to delete the file nor we want that in folder"
8. `git stash pop` : All the files who are backstage come back to the working area
9. `git stash clear`: clearing the files from the stash area

# Resources
[kunal kushwaha youtube](https://www.youtube.com/results?search_query=kunal+kushwaha+git) || [Git official documentation](https://git-scm.com/book/en/v2)



