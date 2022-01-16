---
description: Use our yeoman generator to get started developing a plugin.
---

# Getting Started

## Prerequisites

* Node.js version 16.8+
* Redis 6.2.6+ running on localhost without auth

## Install

Install yeoman and our generator:

```bash
npm install -g yo generator-ekp-nestjs
```

Create a new folder for your plugin:

```
mkdir my-new-plugin
cd my-new-plugin
```

Run the generator and answer the prompts:

```
yo ekp-nestjs
```

Run the app with:

```
nest start --watch
```

Browse to https://alpha.earnkeeper.io/settings and add a plugin with the following url:

```
http://localhost:3001
```

The following menu will appear, your plugin is running!

TODO:

## Make Changes

Open the following file:

