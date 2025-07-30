🚀 Astro Starter Kit: Tailwind + Alpine + Linters

npm create astro@latest -- --template basics
Then add enhancements:

npx astro add tailwind
npm install alpinejs
npm install --save-dev prettier eslint stylelint stylelint-config-standard
📁 Project Structure

/
├── public/
│ └── favicon.svg
├── src/
│ ├── assets/
│ │ └── astro.svg
│ ├── components/
│ │ └── Welcome.astro
│ ├── layouts/
│ │ └── Layout.astro
│ ├── pages/
│ │ └── index.astro
│ └── scripts/
│ └── alpine.js
├── package.json
├── astro.config.mjs
├── tailwind.config.js
├── postcss.config.js
├── .eslintrc.json
├── .prettierrc
├── .stylelintrc.json

🔧 Configuration Notes
Idk i'll write this later lol

<script type="module" src="/scripts/alpine.js" defer></script>

Create src/scripts/alpine.js:

🧞 Commands
Command Action
npm install Install dependencies
npm run dev Start local dev server at localhost:4321
npm run build Build production site to ./dist/
npm run preview Preview your built site
npx prettier . --write Format all files with Prettier
npx eslint . Lint JS/TS files
npx stylelint "\*_/_.css" Lint your CSS/Tailwind styles

📚 Resources
🌐 Astro Docs- https://docs.astro.build/en/getting-started/

🎨 Tailwind CSS- https://tailwindcss.com/

⚡ Alpine.js Docs- https://alpinejs.dev/

📐 Prettier Config - https://prettier.io/docs/configuration.html

# Astro Starter Kit: Basics

```sh
npm create astro@latest -- --template basics
```

> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun!

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src
│   ├── assets
│   │   └── astro.svg
│   ├── components
│   │   └── Welcome.astro
│   ├── layouts
│   │   └── Layout.astro
│   └── pages
│       └── index.astro
└── package.json
```

To learn more about the folder structure of an Astro project, refer to [our guide on project structure](https://docs.astro.build/en/basics/project-structure/).

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
