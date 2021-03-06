# css 定位

## 定位模式

定位模式决定元素的定位方式,它通过 css 的 position 属性来设置,其值可以分为四个

|    值    |   语义   |
| :------: | :------: |
|  static  | 静态定位 |
| relative | 相对定位 |
| absolute | 绝对定位 |
|  fixed   | 固定定位 |

边偏移就是定位的盒子移动到最终位置有 top.bottom left 和 right4 歌
|边偏移属性|示例|描述|
|:-:|:-:|:-:|
|top|top:80px|顶部偏移量,定义元素相对于其父元素上边线的距离.|
|bottom|bottom:80px|底部偏移量,定义元素相对于其父元素下边线的距离.|
|left|left:80px|左侧偏移量,定义元素相对于其父元素左边线的距离.|
|right|right:80px|右侧偏移量,定义元素相对于其父元素右边线的距离.|

## 粘性定位

position:sticky;

粘性定位的特点:

    1. 以浏览器窗口为参照点移动元素(固定定位特点)
    2. 粘性定位占有原来的位置(相对定位特点)
    3. 必须添加top,left,right,bottom 其中一个才有效果
    跟页面滚动搭配使用,兼容性差,le不支持

## 总结

|     定位模式      |    是否脱标    |      移动位置      | 是否常用 |
| :---------------: | :------------: | :----------------: | :------: |
|  static 静态定位  |       否       |   不能使用边偏移   |   很少   |
| relative 相对定位 |  是(占有位置)  | 相对于自身位置移动 |   常用   |
|  fixed 固定定位   | 是(不占有位置) |    浏览器可视区    |   常用   |
|  sticky 粘性定位  | 是(不占有位置) |    浏览器可视区    | 当前较少 |
