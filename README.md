# eslint-config-ds

A shared code style and formatting config for JS projects.

## Installation

```sh
yarn add --dev eslint-config-ds
```

also add `eslint` if not already added

```
yarn add --dev eslint
```

Extend the shared eslint config in your `.eslintrc.js`:

```js
// .eslintrc.js

module.exports = {
  extends: 'eslint-config-ds',
  rules: {
    // Your project-specific rules
  },
};
```

Extend the shared prettier config in your `.prettierrc.js`:

```js
// .prettierrc.js

module.exports = require('eslint-config-ds/.prettierrc');
```
