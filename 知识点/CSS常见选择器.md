CSS中有多种选择器，用于选择要应用样式的HTML元素。以下是一些常见的CSS选择器：

1. 元素选择器（Element Selector）：通过元素名称选择元素。例如，`p`选择所有`<p>`元素，`h1`选择所有`<h1>`元素。
2. 类选择器（Class Selector）：通过类名选择元素。使用`.`前缀，后跟类名。例如，`.my-class`选择具有`class="my-class"`的元素。
3. ID选择器（ID Selector）：通过元素的ID选择元素。使用`#`前缀，后跟ID值。例如，`#my-id`选择具有`id="my-id"`的元素。
4. 属性选择器（Attribute Selector）：通过元素的属性选择元素。例如，`[type="text"]`选择具有`type="text"`属性的元素。
5. 伪类选择器（Pseudo-class Selector）：通过元素的特殊状态或位置选择元素。例如，`:hover`选择鼠标悬停的元素，`:first-child`选择父元素的第一个子元素。
6. 伪元素选择器（Pseudo-element Selector）：选择元素的特定部分或生成的内容。例如，`::before`选择元素的前置内容，`::after`选择元素的后置内容。
7. 后代选择器（Descendant Selector）：选择作为特定元素后代的元素。使用空格分隔元素。例如，`div p`选择所有在`<div>`元素内的`<p>`元素。
8. 直接子元素选择器（Child Selector）：选择作为特定元素直接子元素的元素。使用`>`符号分隔元素。例如，`ul > li`选择所有作为`<ul>`元素直接子元素的`<li>`元素。

这只是一小部分常见的CSS选择器。CSS选择器的组合和嵌套使用可以更精确地选择要应用样式的元素。根据需要选择适当的选择器以实现所需的样式效果。