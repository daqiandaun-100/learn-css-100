# CSS Backgrounds and Borders - CSS 背景与边框

|本期版本| 上期版本
|:---:|:---:
`Sat May 21 05:17:14 CST 2022` | `-`


## 2 - Backgrounds

* [x] 背景颜色: `background-color`
* [x] 背景剪裁: `background-clip` :默认情况下， 背景会延伸到边框所在的区域下层
* [x] 背景图像: `background-image`
* [x] 背景定位: `background-position`: 在偏移量前面指定关键字
* [x] 改变定位框: `background-origin`
* [x] 背景尺寸: `background-size`
* [x] 背景重复: `background-repeat`
* [x] 背景粘附: `background-attachment`
* [x] 简写属性: [`background`](https://developer.mozilla.org/zh-CN/docs/Web/CSS/background)

## 3 - Borders

* [x] 边框的颜色: `border-color`
* [x] 边框的样式: `border-style`
* [x] 边框的宽度: `border-width`
* [x] 简写属性: `border`

## 4 - Rounded Corners

* [x] 外边框圆角: `border-radius`

**`border-radius`**

* 它可以 单独指定水平 和垂直半径， 只要用一个斜杠（ / ）分隔这两个值即可
* 它不仅可以接受长度值，还可以接受百分比值

## 5 - Border Images

* 加载边框图像: `border-image-source`
* 裁剪边框图像：`border-image-slice`
* 边框图像宽度: `border-image-width`
* `border-image-outset`
* 调整重复方式: `border-image-repeat`
* 边框图像简写: `border-image`

## 6 - Miscellaneous Effects

* 阴影效果：[`box-shadow`](https://developer.mozilla.org/zh-CN/docs/Web/CSS/box-shadow):

**`box-shadow`**

* 它支持逗号分隔语法，我们 可以创建任意数量的投影
* 是层层叠加的， 第一层投影位于最顶 层，依次类推
* 不会影响布局，而且也不会 受到 `box-sizing` 属性的影响
* 它们并不会响 应鼠标事件， 比如悬停或点击


## Ref

* [https://www.w3.org/TR/css-backgrounds-3/](https://www.w3.org/TR/css-backgrounds-3/)
* [border-image 的正确用法](https://aotu.io/notes/2016/11/02/border-image/index.html)