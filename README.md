# How to use socket.io with webpack

This repository talk about how to install and work with socket.io using webpack, as a alternative guide to start with Socket.io, because the socket.io start guide is so bad.

## 1. Install all required dependencies

Use your preferred package manager (yarn, npm, ...) to install the follow dependencies:

1. express
2. socket.io
3. socket.io-client
4. webpack
5. webpack-cli

## 2. Create a webpack configuration file

On root folder, create a file called `webpack.config.js` with follow code:

```js
const path = require('path');

module.exports = {
  entry: './src/index.js',
  output: {
    filename: 'main.js',
    path: path.resolve(__dirname, 'dist/js')
  }
};
```
