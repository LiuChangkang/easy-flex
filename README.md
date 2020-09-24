# easy-flex

> 能够快捷使用flex的css组件

```
1、flex-h横向布局，flex-v垂直布局，设置为主轴方向；
2、同时添加inline类名可以使元素变为inline的flex布局；
3、子元素排列方式使用视觉的上(top)下(bottom)左(left)右(right)作为class名；
4、子元素添加flex-fill的class名可以撑开，填充空间；
5、交叉轴默认居中，需要拉伸可以添加stretch类名；
6、如果有其它布局要求，请使用flex布局的官方属性来设置。

具体使用方式可以直接查看example.html
```

#### 配合框架
```
Vue下使用flex-h、flex-v、flex-fill作为标签名的话要让vue识别为自定义标签，需要加入以下代码：

Vue.config.ignoredElements = [
  "flex-h",
  "flex-v",
  "flex-fill"
]

建议直接使用class名称
```

[flex布局的参考地址](http://www.ruanyifeng.com/blog/2015/07/flex-grammar.html)