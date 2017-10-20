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
| git add . | Adds file contents to the index |
| git add foldername/ | Adds a folder to the index |
| git commit | Record changes to the repository. You need to send a commit message. |
| git commit -m "Commit message..." | Record changes to the repository. With the param -m, you can add a message in the same command. |
| git commit -am "Commit message..."| Record changes to the repository. With the param -m, you add file contents to the index and can even add a message in the same command. |
| git log | Show commit logs  |
| git shortlog |   |
| git shortlog -sn |  |
| git status | Show the working tree status |  
