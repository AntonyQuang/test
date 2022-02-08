# Hi there

# This is the Readme.md file used to learn git and github

# Tip: In the command prompt use the command "mkdir NAME" to make a subfolder with the name "NAME" in your current working location

# Tip: In the command prompt use the command cd .. to go back to your desktop

# Here are some git commands:

# git init: Creates a new git respository (repository is sometimes shortened to repo) in the folder the terminal/command promppt is currently located at. For example: If your command prompt was currently located in your desktop, sending the 'git init' command would create a repository there.

# git add Readme.md: Adds a file to the staging area, ready to be committed

# git status: Check the status of what is in the staging area etc, what changes have been made.

# git commit -m "Commit message" : Commits all files added to the staging area. The "Commit message can be any message under 50 characters. Must concisely describe what the changes to the files are.

# git add . : Add all files in the repo

# git checkout -b new: Make a new branch (-b) and change to it (checkout), with that new branch being named "new" (new)

# git checkout master: Going to the "master" branch

# git checkout new: Going to the "new" branch

# git merge master: Takes all the changes in the master branch and merges them into the current branch you are working on, adding those changes

# git merge new: Takes all the changes in the branch named "new" and merges them into the current branch you are working on, adding those changes.

# git remote add origin https://github.com/AntonyQuang/test : Adds the remote repository located in the url (here I used an example) to our local repository. The url is going to be denoted as origin

# git push -u origin master: Push all of the commits onto the remote repository (which we had denoted earlier on as origin) and push them onto the master branch. -u save these settings so you can use git push by itself next time

# git config --global user.name "Antony Quang"

# git config --global user.email "Antony.Quang@googlemail.com"

# git pull origin master: I want to pull from origin's master branch

