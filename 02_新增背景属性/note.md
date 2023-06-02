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