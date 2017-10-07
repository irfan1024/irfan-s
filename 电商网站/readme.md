.col-9 {
    float: left;
    display: block;
    /*这里设置了浮动还设置 relative 的原因有两个: (1)给子元素定位做参考用的.
    (2) z-index,仅对position:relative|absolute|fixed;有效*/
    position: relative;
    min-height: 1px;
}
