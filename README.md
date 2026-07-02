# @opengis/cms

[![NPM version](https://img.shields.io/npm/v/@opengis/cms?style=plain)](https://www.npmjs.com/package/@opengis/cms)

Headless CMS for creating and managing the content of static websites

## Features

- **Real-time Editing** - Update content without stopping or reloading the website.
- **Page Templates** - Use pre-created templates to quickly start your website.
- **Dashboard** - Control panel for quick evaluation of key metrics.
- **Multi-user mode** - Work together with a team on content in real time.
- **User Settings** - Includes functionality for managing user settings, creating user groups, and defining roles with interface permissions.

## Resources and Documentation

- [https://cms.opengis.info](https://cms.opengis.info)


## Install and Usage

### 1. Install the package

```bash
npm i @opengis/cms
```


### 2. Configure the environment

Configure `.env` file

```bash
node --env-file=.env.ip --env-file=.env server
```

### 3. Usage

```js
import { getContents } from "@/utils/cms";

// Get content data from API
let postsData = await getContents("posts");
```

## Contributions

We welcome contributions! Feel free to open issues, suggest features, or submit pull requests.

## License

MIT
