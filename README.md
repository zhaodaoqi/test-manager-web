# test-web

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Run your tests
```
npm run test
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

# test-manager-web

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Run your tests
```
npm run test
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

# 使用
```shell
npm install -g @vue/cli
or
yarn global add @vue/cli
```
# 创建项目
vue create my-app

## 安装 vue 路由模块vue-router和网络请求模块vue-resource
cnpm install vue-router vue-resource --save

cnpm install(i) element-ui -S

安装less依赖

当所有东西都 准备好之后 ：

第一步：

安装less依赖，npm install less less-loader --save

第二步：

修改webpack.config.js文件，配置loader加载依赖，让其支持外部的less,在原来的代码上添加

{

test: /\.less$/,

loader: "style-loader!css-loader!less-loader",

},
现在基本上已经安装完成了，然后在使用的时候在style标签里加上lang=”less”里面就可以写less的代码了(style标签里加上 scoped 为只在此作用域 有效)

（或者

@import './index.less'; //引入全局less文件
）。

(

html中直接引入：

<link rel="stylesheet/less" type="text/css" href="文件路径/styles.less">
<script src="文件路径/less.js" type="text/javascript"></script>
)

# 地址 #

朱小厮

https://blog.csdn.net/u013256816/

程序员江湖

https://blog.csdn.net/a724888/





# 开源接口

爱词霸

http://open.iciba.com/dsapi/

必应每日一图
```
<img src="https://api.dujin.org/bing/1366.php" alt="Bing每日图片" />
<img src="https://api.dujin.org/bing/1920.php" alt="Bing每日图片超高清" />

https://cn.bing.com/cnhp/coverstory?d=20181217
id为缺省日期
```
干货集中营

https://gank.io/api

https://open.saintic.com/openapi
