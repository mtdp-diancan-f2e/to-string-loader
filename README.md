# to-string loader for prajna

## Usage

```js
{
    test: /\.ts$/,
    use: [
        'to-string-loader',
        'awesome-typescript-loader',
        'source-map-loader',
    ],
    enforce: 'pre'
}
```

Don't forget to polyfill `require` if you want to use it in node.

See `webpack` documentation.
