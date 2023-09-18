# Installation via Tailwind CLI

## Tailwind CSS Project setup using a Tailwind CLI

### ✅ Steps to follow to complete Tailwind CSS Setup Successfully

1.  Start by initializing the project using npm

    \`npm init -y\`
2. This command creates a package.json file in our project directory
3.  Install `tailwindcss` via npm \


    ```
    ‌npm install -D tailwindcss
    ```
4.  Create your `tailwind.config.js` file.\


    ```
    npx tailwindcss init
    ```
5.  Add the paths to all of your template files in your `tailwind.config.js` file.\


    ```javascript
    /** @type {import('tailwindcss').Config} */
    module.exports = {
      content: ["./src/**/*.{html,js}"],
      theme: {
        extend: {},
      },
      plugins: [],
    }
    ```
6.  Add the Tailwind directives to your CSS\


    {% code title="src/index.css" overflow="wrap" lineNumbers="true" %}
    ```css
    @tailwind base;
    @tailwind components;
    @tailwind utilities;
    ```
    {% endcode %}
7.  Start the Tailwind CLI build process\
    Run the CLI tool to scan your template files for classes and build your CSS.\


    ```
    npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
    ```
8.  Start using Tailwind in your HTML\


    ```
    <!doctype html>
    <html>
    <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <link href="/dist/output.css" rel="stylesheet">
    </head>
    <body>
      <h1 class="text-3xl font-bold underline">
        Hello world!
      </h1>
    </body>
    </html>
    ```
