# Store to learn Nuxt 3

## Introduction

This project was created to improve my own knowledge about Nuxt technology. Feel free to fork, modify, start an issue and or only 
download this repo and run it on your local environment to see how it's working.

Take a look into [Store project](https://cozy-macaron-f1b4b3.netlify.app/) deployed at Netlify.

## The journey up to this point

At this point in the project timeline I'm capable to understand:
- How to install the base project;
- How to create new pages and apply routes to navigate them;
- How to create new pages that will receive and render params values;
- How to create layouts to reusing code;
- How to install third libraries like **Tailwind CSS** using Nuxt modules;
- How to apply styles to the project using the tailwind.css default file; 
- How to hydrate variables with API requests `fetchData(uri)`;
- How to create custom error pages based on HTTP status code;
- How to work with head tags to add metadata, description and title for SEO in a global way or customized on each page through the `<Head>...</Head>` component;
- How to create routes on the server side to protect sensitive data from being exposed with `useFetch(uri)` function using environment variables **(about.vue page)** and much more...

## Code editor

- [VS Code](https://code.visualstudio.com/download)
- [Vue VSCode Snippets](https://marketplace.visualstudio.com/items?itemName=sdras.vue-vscode-snippets) VS Code extension
- [Vue Language Features (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.volar) VS Code extension

## Setup

Locally I like to use [NVM](https://github.com/nvm-sh/nvm) to manage my Node JS setup. During this project development I used:

```bash
Node: v16.20.1
```

Make sure to install the dependencies:

```bash
# yarn
yarn install
```

## Development Server

Start the development server on `http://localhost:3000`:

```bash
# yarn
yarn dev
```

## Production

Build the application for production:

```bash
# yarn
yarn build
```

Locally preview production build:

```bash
# yarn
yarn preview
```

### Check out: 
- The [Nuxt deployment documentation](https://nuxt.com/docs/getting-started/deployment) for more information.
- The [Fake Store API](https://fakestoreapi.com/) used in this project.
- The [Currency API](https://currencyapi.com/) used in this project.
- The [NuxtTailwind](https://tailwindcss.nuxtjs.org/getting-started/setup/) used in this project.
- The [Netlify](https://www.netlify.com/) platform that I used to make this project deployment.
- The [The Net Ninja](https://www.netlify.com/) awesome Nuxt 3 crash course tutorial.

Or... Look at the [Nuxt 3 documentation](https://nuxt.com/docs/getting-started/introduction) to learn more like I did.