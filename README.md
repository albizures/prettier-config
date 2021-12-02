# Prettier config

> Shared Prettier config for all my projects

## Installation

```bash
  yarn add --dev prettier @albizures/prettier-config
```

then in `prettier.config.js`

```js
module.exports = require('@albizures/prettier-config');
```

### Svelte Projects

In addition to the previus dependencies

```bash
  yarn add --dev prettier-plugin-svelte
```

then in `prettier.config.js`

```js
module.exports = require('@albizures/prettier-config/svelte');
```

## Feedback

If you have any feedback, please reach out to me at [@albzrs](https://twitter.com/albzrs)

## License

[MIT](https://choosealicense.com/licenses/mit/)
