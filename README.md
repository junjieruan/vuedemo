# vuedemo

> A Vue.js project

> 基于Vue2.0编写的PC端商品购物平台，主要划分为以下几个方面：
组件、Vue相关概念(参考官方api)、功能接口，vue-cli环境搭建和vue-router等常用插件安装和配置、Vuex插件的安装和使用

``` bash
# 组件
父子组件之间的通信：父->子，子组件中的props选项；子->父，子组件中$emit

# Vue相关概念(参考官方api)
1.全局api：	Vue.component用于添加全局组件；Vue.use用于注册Vue-Router，Vuex等插件，然后方能使用
2.选项：可在Vue实例中定义的选项字段(el,template等)
3.实例属性/方法：获取实例化对象中的某个数据或绑定某个方法($开头)
4.指令：写在模板标签里面(v开头)
5.内置组件

# 功能接口
1.自定义事件绑定：子组件中触发事件时通过$emit调用父组件中自定义的事件并传参
2.表单事件绑定：表单数据双向绑定v-model，各种修饰符
3.单多选下拉框
计算属性computed选项和数据监听watch选项
4.父组件内容插到子组件：slot插槽
5.内置组件transition：CSS实现过渡效果或JS实现过渡效果
6.自定义指令
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
