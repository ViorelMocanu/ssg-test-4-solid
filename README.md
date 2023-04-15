# ssg-test-4-solid

A test to see which of the Static Site Generators I should use for my personal website and blog.

[![Netlify Status](https://api.netlify.com/api/v1/badges/ecd91f8c-d29b-4d5d-b5c7-77c4107edb75/deploy-status)](https://app.netlify.com/sites/flourishing-maamoul-8b9654/deploys)

# SolidStart

Everything you need to build a Solid project, powered by [`solid-start`](https://start.solidjs.com);

## Creating a project

```bash
# create a new project in the current directory
npm init solid@latest

# create a new project in my-app
npm init solid@latest my-app
```

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

Solid apps are built with _adapters_, which optimise your project for deployment to different environments.

By default, `npm run build` will generate a Node app that you can run with `npm start`. To use a different adapter, add it to the `devDependencies` in `package.json` and specify in your `vite.config.js`.