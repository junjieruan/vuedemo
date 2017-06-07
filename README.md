# vuedemo

> A Vue.js project

> 基于Vue2.0编写的PC端商品购物平台，主要划分为以下几个方面：
组件、Vue相关概念(参考官方api)、功能接口，vue-cli环境搭建和vue-router等常用插件安装和配置、Vuex插件的安装和使用

``` bash
# 组件
1.父子组件之间的通信：父->子，子组件中的props选项；子->父，子组件中$emit
2.单文件组件(template和style和script在一个vue文件中，有利于组件化)

# Vue相关概念(参考官方api)
1.全局api：	Vue.component用于添加全局组件；Vue.use用于注册Vue-Router，Vuex等插件，然后方能使用
2.选项：可在Vue实例中定义的选项字段(el,template等)
3.实例属性/方法：获取实例化对象中的某个数据或绑定某个方法($开头)
4.指令：写在模板标签里面(v开头)
5.内置组件

# 功能接口
1.标签属性v-bind和条件渲染v-if/v-show
2.循环v-for
3.内置事件绑定v-on
4.自定义事件绑定：子组件中触发事件时通过$emit调用父组件中自定义的事件并传参
5.表单事件绑定：表单数据双向绑定v-model，各种修饰符
6.单多选下拉框
计算属性computed选项和数据监听watch选项
7.父组件内容插到子组件：slot插槽
8.内置组件transition：CSS实现过渡效果或JS实现过渡效果
9.自定义指令

# vue-cli脚手架安装
1.cmd命令行中 npm install -g vue-cli  . (执行vue看是否安装vue-cli成功)
2.cmd进入想生成项目的路径,执行vue init webpack vuejs-2.0
3.一路回车，后面三个选No即创建项目成功
4.进入项目路径，执行npm install安装package，然后执行npm run dev运行项目(在localhost启动测试服务器)或者执行npm run build生成上线目录(部署)

# vue-router路由安装
项目路径下执行:npm install vue-router

# vue-resource实现ajax获取数据
cnpm install vue-resource 安装Vue-resource

# Vuex实现全局变量的控制
项目路径下执行:npm install vuex

# json-server模拟数据
1.cnpm install json-server 安装json-server
2.在build/dev-server.js中添加json-server的配置
3.在config/index.js中配置代理选项
```

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

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
