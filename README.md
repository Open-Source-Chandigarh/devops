# Creating the DevOps Journey


DevOps is a culture, not a role. The purpose of DevOps is to enable faster delivery of higher quality software. DevOps is not just limited to a set of tools or a paradigm–it is often designated as the intersection between culture, processes, and tools. Through continuous learning and improvement, engineers are able to improve quality and deliver products faster to market, thus increasing user satisfaction and ROI.



# Setting up Locally

This website is built using [Docusaurus 2](https://docusaurus.io/), a modern static website generator.

### Installation

```
$ yarn
```

### Local Development

```
$ yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ yarn build
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
