# wbw-test

> A Vue.js project

一个用来分享组件的框架

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build
```

For detailed explanation on how things work, consult the [docs for vue-loader](http://vuejs.github.io/vue-loader).

该项目是先

```bash
vue init webpack-simple project-name
```

创建一个简单的webpack项目

参考网址：https://www.cnblogs.com/yalong/p/10388384.html



```bash
npm login
//按照提示输入帐号，密码，邮箱
npm version patch //更新补丁,还有minor，major两个  分别对应major.minor.patch分别对应版本号1.1.1
npm publish//发布插件

//可以将自己的组件发布到npm上，可以供别人下载使用
//使用方式就是跟一般插件一样
```

此时源码是公开的,如果你不想公开源码，你可以`npm run build`之后，你可以把

`.gitignore`里面不上传src文件

```javascript
删除已经发布的包
  npm unpublish --force //强制删除，这个是撤销24小时发布的包，有些包发布久了，这个方法不会再管用了。
  npx force-unpublish package-name '原因描述' //是删除已经发布好的包
```

