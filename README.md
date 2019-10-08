# eslint-plugin-truffle

ESLint plugin for Truffle development. It provides a custom environment containing Truffle global variables.

## Usage

In your `.eslintrc` file, add:

```javascript
{
  // ...
  "env": {
    // ...
    "mocha": true, // for test files
    "truffle/globals": true // same as "truffle/truffle": true
  },
  "plugins": [
    // ...
    "truffle"
    // ...
  ]
  // ...
}
```
