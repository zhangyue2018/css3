## BFC--Block Formatting Context--块格式化上下文
    浮动、绝对定位元素、不是块盒子的块容器（如inline-block、table-cells和table-captions），以及overflow属性的值除visible以外的块盒，将为其内容创建新的块格式化上下文。

    更加通俗的描述：
    1.BFC是Block Formatting Context（块级格式上下文），可以理解成元素的一个“特异功能”。
    2.该"特异功能"在默认的情况下处于关闭状态；当元素满足了某些条件后，该“特异功能”被激活。
    3.所谓激活“特异功能”。专业点说就是：该元素创建了BFC（又称：开启了BFC）。

## 开启了BFC能解决什么问题
    1.元素开启BFC后，其子元素不会再产生margin塌陷问题
    2.元素开启BFC后，自己不会被其他浮动元素锁覆盖
    3.元素开启BFC后，就算其子元素浮动，元素自身高度也不会塌陷

## 哪些元素开启了BFC
    1.根元素--html自动默认开启了BFC
    2.浮动元素--float属性
    3.绝对定位、固定定位的元素
    4.行内块元素
    5.表格单元格：table、thead、tbody、tfoot、th、td、tr、caption
    6.overflow的值不为visible的块元素
    7.弹性盒子和盒子里的伸缩项目---flex
    8.多列容器
    9.column-span为all的元素（即使该元素没有包裹在多列容器中）
    10.display的值，设置为flow-root