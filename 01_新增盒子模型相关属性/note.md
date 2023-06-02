## resize： 调整盒子大小
    none：不允许用户调整元素大小（默认）
    both：用户可以调节元素的宽度和高度
    horizontal：用户可以调节元素的宽度
    vertical：用户可以调节元素的高度 
    注：必须同时设置overflow属性，resize属性才生效

## box-shadow 盒子阴影
    语法：box-shadow: h-shadow v-shadow blur spread color inset;
    h-shadow：水平阴影的位置，必填，可以是负值
    v-shadow：垂直阴影的位置，必填，可以是负值
    blur：可选，模糊距离
    spread：可选，阴影的外延值
    color： 可选，阴影的颜色
    inset： 可选，将外部阴影改为内部阴影

    注：box-shadow的默认值是none