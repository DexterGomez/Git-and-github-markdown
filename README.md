# Git & github/markdown

## The command line

**Create and delete directories**

*mkdir newfolder*  
This command serve to create a foler.

*rmdir examplefolder*  
This command delete a empity folder.

*rm -rf examplefolder*  
Delete a folder and the files inside.

**Navigate**

*cd directory*  
Change to the directory writed.

*ls*  
Show the contend of the currently directory.

*ls -l*  
Show content and its details of the currently directory.

*ls -lR*  
Show files in a recursive way.

**Compare**

*diff file1 file2*  
With this command you compare the files line by line.

*cat examplefile*  
Show the content of a file.

*tac examplefile*  
Show the content of a file upside down.

*more examplefile*  
Show all the content of a file in the console.

*less examplefile*  
Show the content of a file in a interective window.

*wc examplefile*  
Show us the size of a file in lines, words and bytes.

*head examplefile*  
Show us the first part of a file, you can mix up it with the command -n and a number to see an specific number of lines.

*tail examplefile*  
Show us the last part of a file, can be mixed up with the same format -n and number like the last command before.

**Find files, folders and inside files**

*find . -name python1.py*  
Look for a in the choosed directory.

*locate "c files"*  
Look for that thing in all directories of the computer.

*grep "hola mundo" example.c*  
Look for an string of characters in a specific file.

**Create and edit text files**

*vim examplefile*  
Create or edit a file using Vim text editor.

*name examplefile*  
Create or edit a file using nano.

*touch newfile*  
Create an empity file.

*echo "Hiiiii" > introduction.txt*  
Puts the words in a new file or rewrite a file, use ">>" if you don't want to rewrite the file.

**Get the state of the computer**

*pwd*  
Show us the currently direction of directory.

*hostname*  
Show the name of the computer.

*whoami*  
Show the user name.

*history*  
Show us a list of the lastest commands in the console.

## The git / github

**Initial configuration**

*git config --global user.email "example@domain.com"*  
Configure the email of the user.

*git config --global user.name "UserName"*  
Configure the username.

**Starting a project from zero or cloning an existing repository**

*git init*  
Create a new project in the currently directory.

*git clone URL*  
Clone a remote project.

**Basic workflow commands to stage and commit**

*git add examplefile*  
Add a file to the stage area.

*git commit -m "comment"*  
Commit the file with a commentary.

*git status*  
Show the status of the files.

*git log*  
Show the status of the commits.

**Push to a remote repository**

*git push -u origin*  
Upload the commits to the remote repository.

*git pull origin*  
Download the changes from the repository to the local directory.

**Branches**

*git branch newbranch*  
Create a new branch.

*git checkout newbranch*  
Change the branch where you are.

*git merge otherbranch*  
Mix the currently branch with other branch.

*git branch -d examplebranch*  
Delete a branch.

*git branch --list*  
Show a list of the branches.

**gitflow**


*Author: Dexter Enrique Gómez Ek*
