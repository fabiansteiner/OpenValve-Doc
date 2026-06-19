# OpenValve Documentation Website

This repository contains the Docusaurus documentation website for OpenValve.

The website is hosted with GitHub Pages and is available at:

https://docs.open-valve.com

## Project structure

```text
OpenValve-Doc/
  docs/                 Documentation pages
  static/               Static files copied into the build output
    CNAME               Custom domain for GitHub Pages
    img/                Images used by the documentation
  src/                  Custom theme files and CSS
  docusaurus.config.js  Docusaurus configuration
  sidebars.js           Sidebar structure
  package.json          Project scripts and dependencies
```

The editable source files are stored on the `main` branch.

The generated website is deployed to the `gh-pages` branch.

## Install dependencies

Run this once after cloning the repository:

```cmd
npm install
```

## Start the local development server

Run:

```cmd
npm run start
```

This starts the local development server.

By default, the website is available at:

```text
http://localhost:3000
```

## Build the website

Run:

```cmd
npm run build
```

This creates a production build in the `build/` folder.

Use this before deploying to make sure the website builds without errors.

## Preview the production build locally

After building the website, run:

```cmd
npm run serve
```

This serves the generated production build locally.

Use this to check the final built website before deployment.

## Test a specific locale

To start the development server for a specific locale, use:

```cmd
npm run start -- --locale de
```

Replace `de` with the locale you want to test.

For example:

```cmd
npm run start -- --locale en
npm run start -- --locale de
```

Docusaurus can only run one locale at a time in development mode.

## Build a specific locale

To build only one locale, use:

```cmd
npm run build -- --locale de
```

Replace `de` with the locale you want to build.

To build the default configuration, use:

```cmd
npm run build
```

## Deploy to GitHub Pages

Before deploying, commit and push the current source files to `main`:

```cmd
git add .
git commit -m "Update docs"
git push origin main
```

Then deploy the generated website to the `gh-pages` branch:

```cmd
set GIT_USER=fabiansteiner
npm run deploy
```

Or as a single command in Windows cmd:

```cmd
set GIT_USER=fabiansteiner&& npm run deploy
```

After deployment, GitHub Pages serves the website from the `gh-pages` branch.

## Custom domain

The custom domain is configured with the file:

```text
static/CNAME
```

The file should contain exactly:

```text
docs.open-valve.com
```

The DNS configuration should point the `docs` subdomain to GitHub Pages using a CNAME record:

```text
docs → fabiansteiner.github.io
```

In the GitHub repository settings, GitHub Pages should be configured to use:

```text
Branch: gh-pages
Folder: /root
Custom domain: docs.open-valve.com
```

After GitHub verifies the domain, enable:

```text
Enforce HTTPS
```

## Typical update workflow

For normal documentation updates, use this workflow:

```cmd
npm run build
git add .
git commit -m "Update docs"
git push origin main
set GIT_USER=fabiansteiner&& npm run deploy
```

This keeps the source files on `main` and publishes the built website to `gh-pages`.
