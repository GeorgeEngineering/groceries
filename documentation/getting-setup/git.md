While being in the main branch. Switching to a feature branch:

git checkout -b groceries#4-creating-react-project

Creating the readme markdown file.

echo "Groceries Application" >> README.md

Initializing the Git repository.

git init

Adding the README file to the Git staging area.

git add README.md

Commiting the README file.

git commit -m "groceries#4 - Adding the README.md file to the remote Git repository."

Rename the existing main branch.

git branch -M main

Had to use this command to fix an error while pushing the changes to Git.
git config remote.origin.push HEAD