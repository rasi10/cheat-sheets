# Git 

### Installation (Ubuntu!)
sudo apt-get install git 

### Configuration (basic configuration)
- git config --global user.name "YOUR NAME"
- git config --global user.email YOUR_EMAIL@email.com
- git config --global core.editor gedit

### Useful Commands

| Command | Description |
| ------ | ------  |
| **git add** | Adds file contents to the index |
| git add . | Adds all the untracked changes to the index  |
| git add foldername/ | Adds a folder to the index |
| **git commit** | Record changes to the repository. You need to send a commit message. |
| git commit -m "Commit message..." | Record changes to the repository. With the param -m, you can add a message in the same command. |
| git commit -am "Commit message..."| Record changes to the repository. With the param -m, you add file contents to the index and can even add a message in the same command. |
| **git checkout** | Switch branches or restore working tree files |
| git checkout filename| Restore a file to a state before it being edited  |
| **git diff** | Show changes between commits, commit and working tree, etc |
| git diff --name-only | Show changes between commits. Name-only shows only the name of the file that was modified.|
| **git help** |  Display help information about git  |
| git help checkout | Example of how to check details on how to use 'git help'  |
| git help -a |  Displays the available subcommands  |
| git help -d |  Displays some concept guides, e.g. tutorial, etc.  |
| git help everyday |  Displays information about the concept guide "tutorial", which is useful commands for everyday situations/usage.  |
| git help tutorial|  Displays information about the concept guide "tutorial".|
| **git log** | Show commit logs  |
| git log --author="Rafael"| Show commit logs. Filtering by author  |
| git log --author="Rafael"| Show commit logs. Filtering by author  |
| git log --decorate | Show commit logs  |
| git log --graph | Show commit logs in a graph.  |
| git shortlog | Show commit logs in a shorter format than the git log.  |
| git shortlog -sn | Show commit logs in a even shorter format. |
| **git show** | Shows differences, files that were removed/created, etc. |
| git show fwe239823(<-HASH) | Shows details of a specific commit, that you informed the hash of. |
| **git status** | Show the working tree status |  
