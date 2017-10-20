# Git - cheat sheet

## Installation (Ubuntu!)
sudo apt-get install git 

## Configuration (basic configuration)
```sh
- git config --global user.name "YOUR NAME"
- git config --global user.email YOUR_EMAIL@email.com
- git config --global core.editor gedit
```
**Checking the details of the configuration:**
```sh
git config user.name   (prints the name of the user)
git config --list  (prints a list with the details of the configurations)
```
## Useful Commands

| Command | Description |
| ------ | ------  |
| **_git add_** | Adds file contents to the index | 
| git add . | Adds all the untracked changes to the index  |
| git add foldername/ | Adds a folder to the index |
| **_git branch_** |  |  
| **_git clone_** | Clone a repository into a new directory. e.g. "git clone my-repo-on-github" |  
| **_git commit_** | Record changes to the repository. You need to send a commit message. |
| git commit -m "Commit message..." | Record changes to the repository. <br/>With the param -m, you can add </br> a message in the same command. |
| git commit -am "Commit message..."| Record changes to the repository.<br/> With the param -m, you add file contents to the index and can even add a message in the same command. |
| **_git checkout_** | Switch branches or restore working tree files |
| git checkout filename| Restore a file to a state before it being edited.<br/> (If done before adding or commiting the file.)  |
| **_git diff_** | Show changes between commits, commit and working tree, etc |
| git diff --name-only | Show changes between commits. Name-only shows only<br/> the name of the file that was modified.|
| **_git fetch_** | Downloads objects and refs from another repository  |  
| git fetch --all | Fetches all remotes  | 
| **_git help_** |  Display help information about git  |
| git help checkout | Example of how to check details on how to use 'git help'  |
| git help -a |  Displays the available subcommands  |
| git help -d |  Displays some concept guides, e.g. tutorial, etc.  |
| git help everyday |  Displays information about the concept guide "tutorial", <br/> which is useful commands for everyday situations/usage.  |
| git help tutorial|  Displays information about the concept guide "tutorial".|
| **_git init_** | Create an empty Git repository or reinitialize an existing one |  
| **_git log_** | Show commit logs  |
| git log --author="Rafael"| Show commit logs. Filtering by author  |
| git log --author="Rafael"| Show commit logs. Filtering by author  |
| git log --decorate | Show commit logs  |
| git log --graph | Show commit logs in a graph.  |
| git shortlog | Show commit logs in a shorter format than the git log.  |
| git shortlog -sn | Show commit logs in a even shorter format. |
| **_git merge_** |  |  
| **_git pull_** | Fetch from and integrate with another repository or a local branch |  
| **_git push_** | Update remote refs along with associated objects |  
| **_git rebase_** |  |  
| **_git reset_** |  |  
| git reset --soft fw239(hash) | Go back to a commit and the keep </br>the modified files added to the next commit. |
| git reset --mixed fw239(hash) | Go back to a specific commit, but </br>do not keep the modified files added to the next stage. i.e. the files will be untracked. |
| git reset --hard fw239(hash) | Go back to a specific commit and removes </br>all the commits that came after the specific one you are going back to. |
| git reset HEAD filename | nano filename <br/> git add .  <br/> git reset HEAD filename  | 
| **_git show_** | Shows differences, files that were removed/created, etc. |
| git show fwe239823(hash) | Shows details of a specific commit, that you informed the hash of. |
| **_git stash_** |  |  
| **_git status_** | Show the working tree status |  

## Useful git flows
**_Flow 1 - Create a remote repository, create a local repository and send the content of your local repo to your remote repo_**
```sh
ADD THE DESCRIPTION OF THE FLOW 
```
```sh
ADD THE SEQUENCE OF COMMANDS WITH COMMENTS.
```





