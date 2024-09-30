Creating a Vite project:
npm create vite@latest groceries-project -- --template react

Installing the Tailwind CSS framework, Post CSS and the Autoprefixer Post CSS plugin.
npm install -F -D tailwindcss postcss autoprefixer

Post CSS: provided plugins

Autoprefixer: a plugin to parse CSS.

Had some issues when installing Tailwind, so I ran these commands:
npm install --save err
npm config set registry http://registry.npmjs.org

Creating the Tailwind CSS config file tailwind.config.js and the PostCSS config file: postcss.config.js
npx tailwindcss init -p

These configuration files will help you customize your project.

Followed the rest of the instructions at:
https://tailwindcss.com/docs/guides/vite