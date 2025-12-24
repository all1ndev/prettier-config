# `@all1ndev/prettier-config`

[@all1ndev](https://github.com/all1ndev) prettier config

## Usage

**Install**:

```shell
npm install --dev @all1ndev/prettier-config
```

- **Add to `package.json`**:

```jsonc
{
	// ...
	"prettier": "@all1ndev/prettier-config",
}
```

- **Add to `.prettierrc.json`**:

```json
"@all1ndev/prettier-config"
```

- **Add to `.prettierrc.js`**:

```js
module.exports = {
	...require("@all1ndev/prettier-config"),
	// ...
};
```

## Release new version

```shell
npx np
```
