# FontAwesome图标
# 参数
| 参数名	| 介绍	|必选	|值类型	|可选值	|默认值|
| -------|------| ----|----- |-------|-----|
|name	|图标名称 |	非|	String|	font-awesome| 所有图标名|	font-awesome|
# 使用方法
基本
```js
// 这样用没有毛病 但是也没什么用
<nx-icon/>

// 指定图标名称
<nx-icon name="github"/>

// 设置行内样式
<nx-icon name="github" style="font-size: 100px;"/>

// 设置 class
<nx-icon name="github" class="icon-class-demo"/>
```
这个组件只是简化了写法而已
```js
<nx-icon name="github"/>
// 等同于
<i class="fa fa-github" aria-hidden="true"></i>
```

# 参考
图标索引

[Font Awesome 中文网](http://www.fontawesome.com.cn/faicons/)

[fontawesome.com](https://fontawesome.com/icons?d=gallery)