# snowpack-plugin-sass
Use the [node-sass](https://github.com/sass/node-sass) to build `.sass/.scss` files from source

## Usage

### Install
```bash
npm install --save-dev snowpack-plugin-sass
```

### Config
add this plugin to your Snowpack config:  

**snowpack.config.json**
```js
{
  "plugins": [
    "snowpack-plugin-sass"
  ]
}
```
*or*
```js
{
  "plugins": [
    ["snowpack-plugin-sass", { /* node-sass options */ }]
  ]
}
```

