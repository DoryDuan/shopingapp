# shoppingapp

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```
For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).


我的笔记
AMD（异步模块定义）是RequireJS在推广过程中对模块定义的规范化产出物，依赖前置
CMD(同步模块定义)是SeaJS在推广过程中对模块定义的规范化产出物，依赖就近
CommonJs规范-通过module.exports来定义，前端浏览器不支持，在nodeJS后端使用的（module.exports,exports.name两种输出方式）

公共的组件放components里面，页面放views里面
项目目录里面src里面的assets和static的区别：assets放组件的资源，里面的资源会进行打包，图片足够小会生成base64，static放页面的资源，不会打包成base64

mock数据的渲染
方法一：build/dev-server.js 可参考vue-music项目
方法二：build/webpack.dev.conf.js  https://segmentfault.com/q/1010000011988039
