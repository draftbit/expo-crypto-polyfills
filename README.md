# Expo Crypto Polyfills

Use this to polyfill crypto-related libraries without having to eject from Expo.

## Usage

In your Expo project, create a metro.config.js file, then set extraNodeModules to this library:

```js
// metro.config.js
const extraNodeModules = require("expo-crypto-polyfills");
module.exports = {
  resolver: {
    extraNodeModules,
  },
};
```
