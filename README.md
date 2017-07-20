# stub-fs

A stubbed implementation of the Node.js "fs" library.

## Rationale

This library was created as a workaround for Webpack users to reference libraries
which, directly or indirectly, reference the Node.js File System API, but which
do not exercise code paths that make use of that API.

## Usage

```
yarn add 'github.com:getoutreach/stub-fs.js.git'
```
