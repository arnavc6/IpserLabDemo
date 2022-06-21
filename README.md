# IpserLabDemo
This is the README.md file, which usually contains important information pertaining to the code. In the case of this repository, it'll contain information on how to use GitHub.

# Basic setup

## Installing Git 

A lot of these setup processes will be different based on your operating system

MacOS: 
1. Install Homebrew: /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
2. Install Git via Homebrew: brew install git

Windows: TBA

## Cloning the repository onto your computer

Click the green "Code" button and access the dropdown menu, then copy the HTTPS link

MacOS: in Terminal, go to the directory you want to copy the project into, then type "git clone <HTTPS link>"

Windows: TBA
  
Visual studio code (frontend): open a new window, click "clone git repository", paste the link into the prompt

NetBeans: go to the Teams option in the top bar, go Remote -> Clone, paste the link into the repository field (https://netbeans.apache.org/kb/docs/ide/git.html)

Once this step is done, you'll have a copy of the code on your computer and you'll be able to access and edit it, though it's important to note that none of your changes will be seen by anyone else unless you push them (more on that later)

# Git Commands
  
## Making changes 
Follow this sequence of commands in order (otherwise it can end up in a merge error) 
  
### Pull
Purpose: pull changes made to the repository while you were working on your changes
Usage: git pull (Terminal), left sidebar source control -> 3 dot menu -> pull (VS Code), top bar teams -> remote -> pull (NetBeans)
### Add
Purpose: tell github that content is being added to your repository
Usage: git add <filename>, most commonly git add . to stage all your changes (Terminal), top bar teams -> add (NetBeans), mostly done automatically in VS Code
### Commit
Purpose: commit changes to the repository with a message to keep track of what was pushes at that point of time
Usage: git commit -m <message detailing changes> (Terminal), top bar teams -> commit (NetBeans), done with push in VS Code
### Push
Purpose: push committed changes to the github repository
Usage: git push (Terminal), left sidebar source control -> 3 dot menu -> push (VS Code), top bar teams -> remote -> push (NetBeans)
  



  
As we are working as a team. 

It would be convenient if we were to work in branches. So that the main version doesn't get any problems which will be used in production whereas the branches will be checked and merged and then deployed into production. 
  

  

