# poi-preset-coffee

Use coffeescript in your Poi project.

## Install

```bash
yarn add coffeescript poi-preset-coffee --dev
```

## Usage

```js
// poi.config.js
module.exports = {
  presets: [
    require('poi-preset-coffee')(options)
  ]
}
```

## API

<!-- Generated by documentation.js. Update this documentation by updating the source code. -->

### presetCoffeescript

Add CoffeeScript support

**Parameters**

-   `options` **[Object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object)** 
    -   `options.loaderOptions` **any** Options for [coffee-loader](https://github.com/webpack-contrib/coffee-loader#options), `babelOptions` defaults to the babel-loader options we use against .js files. (optional, default `{transpile:babelOptions}`)

## License

MIT © [EGOIST](https://github.com/egoist)