# Website

This website is built using [Docusaurus](https://docusaurus.io/), a modern static website generator.

## Installation

```bash
cd collegiumGuides
npm i
npm docusaurus start
```

## Local Development

```bash
npm run serve
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

## Build

```bash
npm run build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

## Deployment

Just paste this into the terminal once you have cd'ed into collegiumGuides. Replace with your user name obviously

```
GIT_USER=DuncanFindlayCollegium CURRENT_BRANCH=main npm run deploy
```
