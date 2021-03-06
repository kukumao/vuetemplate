# vuetemplete

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

## 目录结构
```shell
├── build                      // 编译配置  
├── config                     // 配置相关
├── src                        // 未编译代码
│   ├── api                         // 接口文件
│   ├── assets                      // 资源文件 图片、icon、样式等静态资源
│   ├── common                      // 存放公共js文件
│   │    ├──fetch                       // 请求类
│   │    ├──bus                         // 监听广播类
│   │    ├──config                      // host配置类
│   │    ├──constant                    // 枚举集和全局常量类
│   │    ├──storage                     // 存储集
│   │    ├──utils                       // 公共js方法
│   ├── components                  // 全局公用组件
│   ├── router                      // 路由
│   ├── views                       // 视图文件
│   ├── App.vue                     // 入口页面
│   ├── main.js                     // 入口js 初始化 加载组件等
├── static                     // 第三方不打包资源（原样复制到服务器上面）
├── .babelrc                   // babel-loader 配置
├── .edtorconfig               // 编辑器配置
├── .eslintignore              // eslint 忽略项
├── .eslintrc.js               // eslint 配置项
├── .gitignore                 // git 忽略项
├── .postcssrc.js              // postcss 配置项
├── index.html                 // html模板
├── favicon.ico                // favicon图标
├── package.json               // package.json
└── README                     // 项目说明

```  

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
