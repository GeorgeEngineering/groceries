Explanation of the following commands:

Command that allows you to create a new branch and checkout to it at the same time:
git checkout -b groceries#4-creating-react-project

This command sends text to an existing file called README.md file. If it does not exist then it creates it.
echo "Groceries Application" >> README.md

Commits the changes to the staging area. 
git commit -m "groceries#4 - Adding the README.md file to the remote Git repository."

Rename the branch name. -m or -M flag. -M flag is used to force the rename.
git branch -M main

git config remote.origin.push HEAD