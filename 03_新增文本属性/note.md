## text-shadow：文本阴影
    语法：text-shadow：h-shadow v-shadow blur color
    h-shadow：必须，水平阴影的位置。允许负值。
    v-shadow：必须，垂直阴影的位置。允许负值。
    blur：可选，模糊的距离。
    color：可选，阴影的颜色。

## white-space: 处理空白字符的设置（空白符包括换行符、空格等，可以用来控制文本换行）
    normal: 文本超出边界自动换行，文本中的换行被浏览器识别为一个空格。（默认值）
    pre：原样输出，与pre标签效果相同。
    pre-wrap：在pre效果的基础上，超出元素边界自动换行。
    pre-line：在pre效果的接触基础上，超出元素边界自动换行，且只识别文本中的换行，行首和行尾的空格会忽略。
    nowrap：强制不换行。

## text-overflow:设置文本溢出时的呈现模式
    clip：当内联内容溢出时，将溢出部分裁减掉。（默认值）
    ellipsis：当内联内容溢出块容器时，将溢出部分替换为...
    注：要使text-overflow生效，块容器必须显示定义overflow为非visible值，white-space为nowrap值

## text-decoration:文本修饰
    css3升级了text-decoration属性，使其变成了复合属性
    text-decoration: text-decoration-line || text-decoration-style || text-decoration-color
    text-decoration-line：设置文本装饰线的位置
        none：指定文本无装饰（默认）
        underline:下划线
        overline:上划线
        line-through：贯穿线
    text-decoration-style:文本装饰线条的形状
        solid：实线（默认）
        double：双线
        dotted：点状线条
        dashed：虚线
        wavy：波浪线
    text-decoration-color：文本装饰线条的颜色