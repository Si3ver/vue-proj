# 笔记

挂载点、模板、实例

插值表达式

v-text v-html

模板指令
v-on:   缩写为 @
v-bind: 缩写为 :

双向数据绑定
v-model

计算属性和侦听器
computed、没变的时候会使用上次的缓存值，改变时则会重新计算。
watch

三个常见指令
v-if 会改变DOM
v-show 不会改变DOM,只是display:none
v-for 循环内容的展示

组件开发
全局组件 Vue.component
局部组件 需要注册哦！
HTML使用组件时，需要传值给组件，组件通过props接收值，然后显示值到模板上。

Vue的组件和实例之间的关系
每个Vue组件也都是一个实例
如果不定义摸版，则会使用挂载点内的HTML代码，作为模板。

发布/订阅模式
子组件与父组件通信方式。
