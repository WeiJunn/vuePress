# forEach

- forEach()专门用来对数组进行遍历,该方法需要一个函数作为参数
  forEach()的回调函数会呗调用多次,数组有几个元素,函数就调用几次,forEach()通过回调函数,将元素传递出来
  - 元素的信息将会以参数的形式传递进入回调函数我们可以通过定义形参来获取元素的信息
    forEach()的回调函数一共有三个参数
    1. 当前被遍历的元素
    2. 当前遍历的元素的索引
    3. 当前正在被遍历的数组对象
