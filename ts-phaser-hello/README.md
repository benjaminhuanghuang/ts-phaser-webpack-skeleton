
- 如何使用 Phaser 3 和 TypeScript 在浏览器中构建一个简单的游戏
https://juejin.cn/post/6844903800495407117
https://github.com/mariyadavydova/starfall-phaser3-typescript


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