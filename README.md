# Expo Crypto Polyfills

Use this to polyfill crypto-related libraries without having to eject from Expo. The goal of this library is to continue to work across all Expo-supported ecosystems (ios,android,web)

## Example

Check out [metro.config.js](https://github.com/draftbit/expo-walletconnect-demo/blob/main/metro.config.js) from our Walletconnect Demo

## Usage

In your Expo project, create a metro.config.js file, then set extraNodeModules to this library:

```js
// metro.config.js
module.exports = {
  resolver: {
    extraNodeModules: require("expo-crypto-polyfills"),
  },
};
```
