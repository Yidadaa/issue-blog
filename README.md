# issue-blog

使用 github 的 issue 系统书写博客，获得完善的 markdown 写作支持，免服务器，响应式布局。

> A Vue.js project

## 使用指南

在你的 Github Pages 目录下，新建`index.html`文件，并将以下内容复制进去即可。
```html
<!DOCTYPE html>
<html lang="zh-cn">
  <head>
    <meta charset="utf-8">
    <title>Yidadaa的个人博客</title>
    <meta name="viewport" content="width=device-width,minimum-scale=1.0,maximum-scale=1.0,user-scalable=no">
  </head>
  <body>
    <div id="app"></div>
    <script>
      window.username = 'Yidadaa'
      window.reponame = 'Yidadaa.github.io'
    </script>
    <script src="https://cdn.bootcss.com/fetch/2.0.3/fetch.min.js"></script>
    <script src="https://cdn.bootcss.com/babel-polyfill/6.26.0/polyfill.min.js"></script>
    <script src="http://blog.simplenaive.cn/issue-blog/dist/build.js"></script>
  </body>
</html>
```
对，就这么简单。

## 开发指南

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production
npm run build
```

For detailed explanation on how things work, consult the [docs for vue-loader](http://vuejs.github.io/vue-loader).
