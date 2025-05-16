# Hungry Hippo

## 🧠 Project Overview

We are the **Hungry Hippo** team, and we're developing an innovative tool to enhance Augmentative and Alternative Communication (AAC) devices for children. Our goal is to integrate fun, interactive games that encourage social interaction while providing essential communication support for AAC users. By combining play with practical communication tools, we aim to reduce social isolation and make communication more accessible and enjoyable for children who rely on AAC.

This website is built using [Docusaurus 2](https://docusaurus.io/), a modern static website generator.

### Installation

```
$ yarn
```

### Local Development

```
$ PROJECT_NAME=project-701-aac-the-hungry-hippos yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ PROJECT_NAME=project-701-aac-the-hungry-hippos yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

Using SSH:

```
$ USE_SSH=true yarn deploy
```

Not using SSH:

```
$ GIT_USER=<Your GitHub username> yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.
