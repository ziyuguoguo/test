# test

├── build // 打包构建目录
│   ├── build.js // 打包时执行的文件
│   └── webpack.conf.js // webpack配置文件
├── demo // demo目录，用于启动一个demo页面，查看插件实际效果
│   ├── README.md // 说明文件
│   └── src // demo app源码目录
│       ├── components // 打包时执行的文件
│             └── ComponentDemo.vue // 插件在这里使用
│       └── main.js // 插件在这里被import进来
├── dist // 打包后文件
│   └── your-plugin-name.js // 打包后js文件, 名称跟package.json中name字段一致
├── src // 源码目录
│   └── css // css源码目录
│   └── js // js源码目录
│       └── YourPluginName.vue // 插件文件
├── index.js // 入口文件
├── .babelrc // babel配置
├── .eslintrc.js // eslint配置
├── .gitignore // git忽略规则配置
├── .editorconfig // 编辑器代码格式规则
├── .README.MD // 插件介绍及使用说明等信息
├── package.json // NPM package描述文件，需要修改name和dist字段