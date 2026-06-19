# OpenValve Documentation Page

doc.open-valve.com page: Everything you need to know about OpenValve.

This website is built using [Docusaurus](https://docusaurus.io/), a modern static website generator.


# OpenValve Documentation

This repository contains the documentation website for OpenValve.

It is built using [Docusaurus](https://docusaurus.io/).

The published documentation is available at:

https://docs.open-valve.com

## Development

Install dependencies:

```cmd
npm install
```

Start the local development server:

```cmd
npm run start
```

By default, the local website is available at:

```text
http://localhost:3000
```

## Build

Create a production build:

```cmd
npm run build
```

Preview the production build locally:

```cmd
npm run serve
```

## Locales

Start the development server for a specific locale:

```cmd
npm run start -- --locale de
```

Build a specific locale:

```cmd
npm run build -- --locale de
```

Replace `de` with the locale you want to test.

## Deployment

The source files are kept on the `main` branch.

The generated website is deployed to the `gh-pages` branch and served through GitHub Pages.

Typical deployment workflow:

```cmd
git add .
git commit -m "Update docs"
git push origin main
set GIT_USER=fabiansteiner&& npm run deploy
```

## Custom domain

The custom domain is configured through:

```text
static/CNAME
```

The file contains:

```text
docs.open-valve.com
```
