# @opengis/cms

[![NPM version](https://img.shields.io/npm/v/@opengis/cms?style=plain)](https://www.npmjs.com/package/@opengis/cms)

Headless CMS for creating and managing the content of static websites

## Features

- **Real-time Editing** - Update content without stopping or reloading the website.
- **Page Templates** - Use pre-created templates to quickly start your website.
- **Dashboard** - Control panel for quick evaluation of key metrics.
- **Multi-user mode** - Work together with a team on content in real time.
- **User Settings** - Includes functionality for managing user settings, creating user groups, and defining roles with interface permissions.


## Documentation

For a detailed understanding of `cms`, its features, and how to use them, refer to our [Documentation](https://apidocs.softpro.ua/cms/).

## Get started

### Install

```bash
npm i @opengis/cms
```


### Configuration

Configure `.env` file

```bash
node --env-file=.env.ip --env-file=.env server
```


### Usage

```js
import { getContents } from "@/utils/cms";

// Get posts from API
let postsData = await getContents("posts");
```

## License

MIT
