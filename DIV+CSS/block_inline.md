## 块级元素：
>div、form、h1-h6、hr、p、menu、ul、table、pre

独占一行，默认情况下，宽度自动填满父元素宽度。
## 内联元素：
>span、a、abbr、acronym、b、big、br、cite、em、dfn、img、i、ifont、input、q、select

不会独占一行，宽度随着元素的内容而变化，并且width和height的设置无效，同时在margin和padding的垂直方向上不产生边距效果。
>可以使用display:block;/inline;实现块级元素和行内元素的相互转换。 display:inline/block;none;

## 隐藏DOM元素
display:none;  
> 在不删除元素的情况下通常被JS用来隐藏或显示元素。
视为不存在，且不加载  不占空间
使用该属性后，HTML元素的宽度、高度等各种属性值都将丢失

visibility:hidden;  
> 表示隐藏，但在浏览时保留位置
使用该属性后，HTML元素仅仅是在视觉上看不见(完全透明)，而它所占据的空间位置依旧存在，即依然具有高度、宽度等属性。


