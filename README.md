# vue-skeleton

> A Vue.js project

## 参考资料[Vue页面骨架屏注入实践](https://segmentfault.com/a/1190000014832185)

## Build Setup

``` bash
# install dependencies
npm install

# 在/dist目录下生成一个skeleton.json文件
webpack --config ./webpack.skeleton.conf.js

# 完成骨架屏的注入index.html
node skeleton.js

# serve with hot reload at localhost:8088
npm run dev

# build for production with minification
npm run build

```


