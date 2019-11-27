## 布局

记录常见的布局解决方案


### 水平居中

* 父元素text-align:center；子元素 display: inline-block
* 子元素margin: 0 auto;
* 父元素relative；子元素absolute + left：50% + transform：translateX(-50%)
* 父元素relative；子元素子元素absolute + left：50% + margin-left: 子元素宽度的1/2;
* 父元素display:flex; just-content:center;

### 垂直居中

*

### 水平垂直居中