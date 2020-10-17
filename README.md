# easy-flex
<a href="https://www.npmjs.com/package/easy-flex"><img src="https://img.shields.io/npm/v/easy-flex.svg?sanitize=true" alt="Version"></a>

> 能够快捷使用flex布局的css组件

[Demo & Docs](https://liu_changkang.gitee.io/easy-flex/)

## Installation
```
npm install easy-flex --save

or

yarn add easy-flex
```

### Usage
```
import 'easy-flex'
```

### Tip
```
使用class名：flex-h、flex-v、top、right、bottom、left、center，互相组合可以开发绝大多数的布局。

1、flex-h横向排列，flex-v垂直排列；
2、子元素排列方向使用视觉的上(top)下(bottom)左(left)右(right)作为class名；
3、横向多行布局可在父节点添加wrap类名，子节点需换行的位置使用hr标签换行，兼容性请查阅caniuse；
4、如果有其它布局要求，请使用flex布局的标准属性来设置。

具体使用方式可以直接查看example.html
```

#### 配合框架
```
Vue下使用flex-h、flex-v、flex-fill作为标签名的话要让vue识别为自定义标签，需要加入以下代码：

Vue.config.ignoredElements = [
  "flex-h",
  "flex-v",
  "flex-fill"
];

建议全部使用class名
```

#### 链接
[flex兼容性](https://caniuse.com/?search=css%20flex)

[flex-wrap兼容性](https://caniuse.com/?search=flex-wrap)

[flex布局的参考地址](http://www.ruanyifeng.com/blog/2015/07/flex-grammar.html)