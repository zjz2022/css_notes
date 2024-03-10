在Flex布局中，有两组属性，分别用于控制Flex容器（Container）和Flex项目（Item）的行为和样式。

1. 容器属性（Container Properties）：
   - `display`: 定义容器为Flex容器，可以设置为`flex`或`inline-flex`。
   - `flex-direction`: 定义Flex项目在容器中的排列方向，可以设置为`row`（水平方向，默认值）、`row-reverse`（反向水平方向）、`column`（垂直方向）或`column-reverse`（反向垂直方向）。
   - `flex-wrap`: 定义Flex项目在一行排列不下时是否换行，可以设置为`nowrap`（不换行，默认值）、`wrap`（换行）或`wrap-reverse`（反向换行）。
   - `justify-content`: 定义Flex项目在主轴上的对齐方式，可以设置为`flex-start`（靠左对齐，默认值）、`flex-end`（靠右对齐）、`center`（居中对齐）、`space-between`（两端对齐，项目之间间隔相等）、`space-around`（均匀分布，项目两侧间隔相等）或`space-evenly`（均匀分布，项目之间和两侧间隔相等）。
   - `align-items`: 定义Flex项目在交叉轴上的对齐方式，可以设置为`flex-start`（靠上对齐）、`flex-end`（靠下对齐）、`center`（居中对齐）、`baseline`（基线对齐）或`stretch`（拉伸以填满容器，默认值）。
   - `align-content`: 定义多行Flex项目在交叉轴上的对齐方式，只在有多行时生效，可以设置为`flex-start`（靠上对齐）、`flex-end`（靠下对齐）、`center`（居中对齐）、`space-between`（两端对齐，行之间间隔相等）、`space-around`（均匀分布，行两侧间隔相等）或`stretch`（拉伸以填满容器，默认值）。
2. 项目属性（Item Properties）：
   - `order`: 定义Flex项目的排列顺序，可以设置为整数值，值越小越靠前，默认值为0。
   - `flex-grow`: 定义Flex项目在剩余空间中的放大比例，默认值为0，不放大。
   - `flex-shrink`: 定义Flex项目在空间不足时的缩小比例，默认值为1，可以设置为0以禁止缩小。
   - `flex-basis`: 定义Flex项目在分配多余空间之前的初始大小，默认值为`auto`，可以设置为具体长度值。
   - `flex`: 是`flex-grow`、`flex-shrink`和`flex-basis`的缩写属性。
   - `align-self`: 定义单个Flex项目在交叉轴上的对齐方式，覆盖容器的`align-items`属性，可以设置为`auto`（继承父容器的`align-items`值）、`flex-start`（靠上对齐）、`flex-end`（靠下对齐）、`center`（居中对齐）、`baseline`（基线对齐）或`stretch`（拉伸以填满容器）。

通过设置这些容器属性和项目属性，可以控制Flex布局的外观和行为，实现灵活的、自适应的页面布局。