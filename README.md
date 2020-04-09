# prettier-config

Standard [Prettier configuration](https://prettier.io/docs/en/configuration.html) for Labs team projects.

## Installation

```bash
yarn add --dev @prisma-labs/prettier-config
```

## Usage

In your `package.json`

```json
{
  "prettier": "@prisma-labs/prettier-config"
}
```

If you wish you _extend_ these settings then in your `.prettierrc.js`

```js
module.exports = {
  ...require('@prisma-labs/prettier-config'),
  semi: false,
}
```
