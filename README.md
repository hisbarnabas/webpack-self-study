# Getting Started Webpack
URL: https://webpack.js.org/guides/getting-started/

### Install NPM + NPX
```
$ sudo apt install npm
$ sudo npm install -g npx
```

### Install NPM + initial setup
```
$ mkdir webpack-demo
$ cd webpack-demo
$ npm init -y
$ npm install webpack --save-dev
$ npm install webpack-cli --save-dev
```

### Install Dependencies
```
$ npm install --save lodash
```

### Directories & Files
```
  webpack-demo
  |- package.json
  |- /dist
    |- index.html
  |- /src
    |- index.js
```

### Run Webpack
```
$ npx webpack

OR - using configuration file

$ npx webpack --config webpack.config.js
```
