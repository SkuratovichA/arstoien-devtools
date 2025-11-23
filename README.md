# @arstoien/devtools

Shared ESLint and Prettier configurations for Arstoien projects.

## Installation

```bash
npm install --save-dev @arstoien/devtools
# or
yarn add -D @arstoien/devtools
```

## Usage

### ESLint Configuration

Create an `eslint.config.js` file in your project root:

```javascript
const { eslintrc } = require('@arstoien/devtools');

module.exports = eslintrc;
```

### Prettier Configuration

Create a `.prettierrc.js` file in your project root:

```javascript
const { prettierrc } = require('@arstoien/devtools');

module.exports = prettierrc;
```

## Features

### ESLint
- TypeScript support with strict type checking
- React hooks linting
- Import organization and unused imports detection
- Lodash best practices
- Consistent code style enforcement

### Prettier
- Consistent formatting with 2-space indentation
- Single quotes for strings
- Trailing commas (ES5)
- 100 character line width
- Tailwind CSS class sorting support

## Peer Dependencies

This package requires the following peer dependencies:

- `eslint` ^9.0.0
- `prettier` ^3.0.0
- `typescript` ^5.0.0

## License

MIT