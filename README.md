# smart-px2rem-loader

a [webpack](http://webpack.github.io/) loader for [px2rem](https://github.com/songsiqi/px2rem)

[![NPM version][npm-image]][npm-url]
[![Build status][travis-image]][travis-url]
[![Downloads][downloads-image]][downloads-url]

[npm-image]: https://img.shields.io/npm/v/smart-px2rem-loader.svg
[npm-url]: https://npmjs.org/package/smart-px2rem-loader
[travis-image]: https://img.shields.io/travis/smackgg/smart-px2rem-loader.svg
[travis-url]: https://travis-ci.org/smackgg/smart-px2rem-loader
[downloads-image]: http://img.shields.io/npm/dm/smart-px2rem-loader.svg
[downloads-url]: https://npmjs.org/package/smart-px2rem-loader

## Install

`npm install smart-px2rem-loader`

## webpack config

```
{
  loaders: [{ test: /\.css$/, loader: 'style!css!px2rem?remUnit=75&remPrecision=8' }]
}
```

## excludes

```
{
  loaders: [{ test: /\.css$/, loader: 'style!css!px2rem?remUnit=75&remPrecision=8&excludes[]=border' }]
}
```


Please see [px2rem](https://github.com/songsiqi/px2rem) for more information about query parameters of px2rem.
