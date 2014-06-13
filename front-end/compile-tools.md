## 前端集成－打包预编译流程

* 脚本类

  1. Ant
  2. Maven
  3. Makefile
  4. Grunt
  5. Gulp

* CI

  1. Jenkins
  2. Travis
  3. Semaphore
  4. Hudson

* 测试工具

  1. karma
  2. selenium-webdriver (js: webdriver)

*代码规范

  1. jshint

* notice:

  `
  与node 保持统一的模块风格，使用jshint统一代码风格，还可以提供对coffee的支持
  编译阶段解决模块依赖，可根据发布的版本号更新local-storage或application中的代码。
  组件化开发，一个组件的js、css、模板最好都在一个目录，开发起来方便，不用把生命都浪费在翻目录打开文件上。
  提供对第三方模版引擎的支持
  js/css/图片 压缩。
  开发体验要好，可以和karam集成，livereload一个都不能少。
  本地/线上代理，预览本地文件，也能方便抓取或访问线上数据，方便调
  `
