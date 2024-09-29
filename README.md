# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh


---

# Instructions used at the beginning of this project:
echo "Groceries Application" >> README.md

Initializing the Git repository.
git init

Adding the README file to the staging area.
git add README.md

Commiting the README file.
git commit -m "groceries#4 - Adding the README.md file to the remote Git repository."

git branch -M groceries#4-creating-react-project

git branch -M main

git push -u origin groceries#4-creating-react-project

Had to use this command to fix an error while pushing the changes to Git.
git config remote.origin.push HEAD

Creating a Vite project:
npm create vite@latest groceries-project -- --template react

Installing Tailwind
npm install -F -D tailwindcss postcss autoprefixer

Had some issues when installing Tailwind, so I ran these commands:
npm install --save err
npm config set registry http://registry.npmjs.org

Creating the Tailwind CSS config file tailwind.config.js and the PostCSS config file: postcss.config.js
npx tailwindcss init -p



