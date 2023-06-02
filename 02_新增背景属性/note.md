## background-origin:设置背景图的原点（只对背景图片有效）
    padding-box:从padding区域开始显示背景图片--默认值
    content-box：从content区域开始显示背景图片
    border-box：从border区域开始显示背景图片
    注：原点是各区域的左上角

## background-clip: 设置背景图的向外裁剪的区域--也就是超出设置的区域就不显示了，此属性对背景图和背景颜色都有效
    border-box：从border区域开始裁剪向外背景--默认值
    padding-box：从padding区域开始向外裁剪背景
    content-box：从content区域开始向外裁剪背景
    text：背景图只呈现在文字上
    注：若值为text，那么background-clip要加上-webkit-前缀，且文字要设置成透明

## background-size:设置背景图片的尺寸
    1.用长度值指定背景图片大小，不允许负值。 background-size: 300px 200px
    2.用百分比指定背景图片大小，不允许负值。 background-size：100% 100%
    3.auto：背景图片的真实大小。---默认值
    4.contain：将背景图片等比缩放，使背景图片的宽或高（最大的那个），与容器的宽或高相等，再将完整背景图片包含在容器内。注意：可能会造成容器里部分区域没有背景图片
    5.cover：将背景图片等比缩放，直到完全覆盖容器，图片会尽可能全的显示在元素上。注意：背景图片有可能显示不完整。--相对比较好的选择
    注：cover选项，是与contain相对应的，也可以描述为：等比缩放，使背景图片的宽或高（最小的那个），与容器的宽或高相等，然后再将此时多余的图片部分裁掉不显示