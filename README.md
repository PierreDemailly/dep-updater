# dep-updater
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/fraxken/dep-updater/commit-activity)
![MIT](https://img.shields.io/github/license/mashape/apistatus.svg)
![V1.0](https://img.shields.io/badge/version-0.1.0-blue.svg)

npm Dependencies Updater.

## Features

- Upgrade package for you (even for breaking release).
- Run test after each upgrade (and rollback if test fail).
- Create a git commit for each update

## Getting Started

This package is available in the Node Package Repository and can be easily installed with [npm](https://docs.npmjs.com/getting-started/what-is-npm) or [yarn](https://yarnpkg.com).

```bash
$ npm install dep-updater -g
# or
$ npx dep-updater
```

## Usage example
When installed globally the `depup` executable will be exposed in your terminal

```bash
$ cd yourProject
$ depup
```

## Roadmap
- [BUG] Sometimes pkg.current is an Object !
- Detect if the terminal support emoji or not.
- Add argv option to change the default git template.
- Add argv option to force test and commit (avoid option asking).
- Add argv option to force updateAll (or updateWanted).
