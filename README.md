# @dyc5828/prettier-config

Dan's Prettier Configuration

## Install

```shell
yarn add --dev @dyc5828/prettier-config
```

### VSCode

1. Get [Prettier VSCode](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

1. Set `Prettier VSCode` as default formatter and enable on `Format on Save` in VSCode settings. See `.vscode/settings.json`

## Use

Create `prettier.config.js` and use package

```js
module.exports = require('@dyc5828/prettier-config')
```

### Customize Configurations

Edit `prettier.config.js`

```js
module.exports = {
  ...require('@dyc5828/prettier-config'),
  semi: true,
}
```
