# vue-mv3-hot-reload

## Project setup
```
npm install
```
After `npm install` move 3x files from `config_files` folder:

  1. `index.js` to `node_modules`->`vue-cli-plugin-browser-extension`
  2. `manifest.js` to `node_modules`->`vue-cli-plugin-browser-extension`->`lib`
  3. `webpack-extension-reloader.js` to `node_modules`->`vue-cli-plugin-browser-extension`->`lib`


### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Community support needed - upgrading to Webpack 5
Although this package is working fine, I stumbled upon a number of issues when upgrading/installing other packages, particularly Webpack 5 dependent. I've had a few attempts upgrading this repo to Webpack 5 which failed. 

Any help upgrading to Webpack 5 would be highly appreciated :)


### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
"# vue-extension-mv3-hot-reload" 
