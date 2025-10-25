# Nightfall Website

A website hosted on Github Pages, to represent the Nightfall server.

This website is built using [Docusaurus](https://docusaurus.io/), a modern static website generator.

## Setup

This website was built with Node 22, but it will work as long as your node version is at least 20.

Ensure you have [Node](https://nodejs.org/en) installed (direct installation or through [Node Version Manager](https://github.com/nvm-sh/nvm)).

Install Dependencies:
```bash
npm ci
```

## Local Development

```bash
npm run start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

## Build

```bash
npm run build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

## Deployment

Deployments are automatic through workflows. No manual action is needed, the workflow will automatically build and deploy when commits are pushed to the main branch.

Pull Requests will run a workflow to test if they build properly.
