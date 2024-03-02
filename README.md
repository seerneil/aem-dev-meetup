# AEM Developer Meetup Site
Our goal is to create an engaging and user-friendly website for hosting developer meetup events. This platform will serve as a centralized hub for tech enthusiasts, software developers, and industry professionals to connect, collaborate, and learn from one another. The website will feature a comprehensive event calendar, an interactive discussion forum, and a directory of local tech communities.

## Environments
- Preview: https://main--aem-dev-meetup--seerneil.hlx.page/
- Live: (https://main--aem-dev-meetup--seerneil.hlx.)live/

## Installation

```sh
npm i
```

## Linting

```sh
npm run lint
```

## Local development

1. Create a new repository based on the `aem-boilerplate` template and add a mountpoint in the `fstab.yaml`
1. Add the [AEM Code Sync GitHub App](https://github.com/apps/aem-code-sync) to the repository
1. Install the [AEM CLI](https://github.com/adobe/helix-cli): `npm install -g @adobe/aem-cli`
1. Start AEM Proxy: `aem up` (opens your browser at `http://localhost:3000`)
1. Open the `{repo}` directory in your favorite IDE and start coding :)
