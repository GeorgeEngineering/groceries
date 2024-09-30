Configuring the template paths

tailwind.config.js

    /** @type {import('tailwindcss').Config} */
    export default {
        content: [
            "./index.html",
            "./src/**/*.{js,ts,jsx,tsx}",
        ],
        theme: {
        extend: {},
        },
        plugins: [],
    }


Adding Tailwind directives to the CSS file. 

index.css

    @tailwind base;
    @tailwind components;
    @tailwind utilities;

Directives refer to Tailwind-specific statements that instruct CSS how to behave.

@tailwind base: injects Tailwind's base styles and base styles registered by plugins

@tailwind components: injects Tailwind's component classes and component classes registered by plugins

@tailwind utilities: injects Tailwind's utility classes and utility classes registered by plugins


Reference:
https://www.freecodecamp.org/news/how-to-install-tailwindcss-in-react/