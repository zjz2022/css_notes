在CSS中，有两个与margin相关的概念：margin传递（margin collapsing）和margin折叠（margin collapsing）。

1. Margin传递：
   当两个垂直相邻的元素具有margin时，它们的垂直margin可能会发生合并，产生称为margin传递的效果。具体规则如下：

   - 如果上一个元素的底部margin和下一个元素的顶部margin相遇，它们会合并为一个margin，取其中较大的值作为合并后的margin。
   - 如果上一个元素的底部margin和下一个元素的顶部margin之间存在其他内容（例如边框、padding、空白等），则不会发生margin传递。

   这种合并只适用于垂直方向的margin，水平方向的margin不会发生传递。

2. Margin折叠：
   当一个元素既有顶部margin又有底部margin时，可能会发生margin折叠，即两个margin合并为一个margin，取其中较大的值作为合并后的margin。具体规则如下：

   - 当相邻的两个元素之间没有边框、padding或空白（如换行符）时，它们的margin会折叠。
   - 当一个元素的顶部margin与其第一个子元素的顶部margin相遇，或者一个元素的底部margin与其最后一个子元素的底部margin相遇时，也会发生margin折叠。

   Margin折叠只会发生在普通文档流中的块级元素上，行内元素、浮动元素、绝对定位元素以及具有`overflow`属性值不为`visible`的元素不会发生margin折叠。

Margin传递和折叠是CSS中常见的现象，它们可能会对元素的布局和间距产生一些意外的效果。了解这些规则可以帮助开发者更好地控制元素之间的间距和布局。