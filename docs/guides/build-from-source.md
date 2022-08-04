import Tabs from "@theme/Tabs";
import TabItem from "@theme/TabItem";

# Build From Source

## Install Dependencies

### Versions

| Software | Version      |
| ---------| -------------|
| node.js  | ~16.16.0 LTS |
| npm      | ~8.16.0      |
| yarn     | 1.22.19      |
| golang   | 1.17         |

### NVM for Node + npm version management

Install `nvm` to manage `node` and `npm` version for building the frontend.

Install [nvm](https://github.com/nvm-sh/nvm) or alternatively [Installing Node.js and npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)

### Node

```
nvm install --lts
npm install -g npm@8.16.0
```
### Yarn

`npm install -g yarn`

## Build

The quickest way to install and update Hetty is via Make:

```
make build
```

Run with [Getting Started](https://hetty.xyz/docs/getting-started#run)
