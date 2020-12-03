# Phaser test

## Setup
Create project
```
npm init
```

Setup typescript 
```
npm i -D typescript
```
create tsconfig.json

Setup webpack
```
npm i -D webpack webpack-cli ts-loader
```
create webpack.config.js

Install phaser
```
npm i phaser
```

Install dev tools
```
npm i -D live-server
```

Create npm script
``
"scripts": {
  "build": "webpack",
  "start": "webpack --watch & live-server --port=8085"
}
```