# A4 Resume Templates

All A4 Resume Templates

## Installation

- Instantly initialize a `NodeJS` project
- Install `tailwindcss` via npm
- Create your `tailwind.config.js` file.
- Install Prettier plugin for Tailwind CSS
- Install [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) for Visual Studio Code
- Start the Tailwind CLI build process

```sh
npm init -y
npm install -D tailwindcss
npm install -D @tailwindcss/forms
npm install -D prettier prettier-plugin-tailwindcss
npx tailwindcss init

npx tailwindcss -i ./src/tailwind.css -o ./docs/style.css --watch
npm run watch
npm run build
```