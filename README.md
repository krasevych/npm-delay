# npm-delay
delay before run next command

## Install

```
$ npm install --save npm-delay
```
or
```
$ yarn add --dev npm-delay
```


## Usage
package.json
```
  "scripts": {
    "dev:server:delay": "run-s delay dev:server:start",
    "delay": "npm-delay 1000",
    "dev:server:start": "node ./src/server.js",
  },
```
