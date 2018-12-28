## Webpack for Javascript only:
* Install webpack modules: npm i -D -g webpack webpack-cli webpack-dev-server(optional)
* Go to 'www.webpackjs.org' and copy start-up codes, then past into webpack.config.js
* In order to convert ES6/ES7/ES8 into ES5, install babel module: go to 'https://github.com/babel/babel-loader' and copy 'npm install -D babel-loader @babel/core @babel/preset-env webpack', then paste into webpack.config.js and execute the commands.
* Create scripts in package.json: 
  "scripts": {
    "watch": "webpack --mode=development --watch",
    "start": "webpack --mode=development",
    "deploy": "webpack --mode=production"
  },
* Execute npm run watch to auto reload files once we have made changes
* Execute npm run deploy before ready to upload to server
