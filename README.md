# babel-preset-es2015-node

> Babel preset for all es2015 plugins needed with latest stable node.

## Install

```sh
$ npm install --save-dev babel-preset-es2015-node
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "presets": ["es2015-node"]
}
```

### Via CLI

```sh
$ babel script.js --preset es2015-node
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  presets: ["es2015-node"]
});
```