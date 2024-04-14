## webpack打包多页面应用基础构建，不使用mvvm库

```js
npm run dev // 9000端口启动本地服务
npm run build // 项目打包
```
 1. 支持多页面打包入口,webpack配置文件中一个`new HtmlWebpackPlgin`对应一个页面配置
 2. 对js根据大小配置分包打包，对js，css进行压缩