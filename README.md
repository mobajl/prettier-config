# @mobajl/prettier-config

Prettier configuration for Mobajl.

## Usage

```sh
$ yarn add -D @mobajl/prettier-config
```

In `package.json` add:

```js
{
	"prettier": "@mobajl/prettier-config"
}
```

Or if you don't want it in your `package.json`:

```sh
$ echo '"@mobajl/prettier-config"' > .prettierrc.json
```

Or if you need to extend it, add `.prettierrc.js`:

```js
module.exports = {
	...require("@mobajl/prettier-config"),
	// Do your thing...
	semi: false,
};
```
