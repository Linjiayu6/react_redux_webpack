# React_Redux_Webpack
keywords: react, redux, webpack

### 1. Init

#### 1.1 create repository

`$ npm init`

#### 1.2 install modules

安装地址参考:
http://zhaoda.net/webpack-handbook/install.html
https://fakefish.github.io/react-webpack-cookbook/
https://vikingmute.gitbooks.io/webpack-for-fools/content/entries/chapter-1.html

### 2. Webpack

配置文件主要分为三个部分
- entry: /src/ 入口文件
- output: /public/ 出口
- module: 模块 要用什么不同的模块来处理各种类型的文件

#### 2.1
- `$ npm install webpack -g`
- `$ npm install html-webpack-plugin --save-dev` 快速生成html
- 配置webpack.config.js, 定义好打包入口文件src, 出口文件public, plugins: HtmlwebpackPlugin可以快速生成html,
并将打包的内容自动引入
- 用`$ webpack` 运行一下