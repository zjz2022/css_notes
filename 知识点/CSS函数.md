CSS函数是一种用于处理值或生成样式的函数，可以在CSS样式表中使用。CSS函数可以接受一个或多个参数，并返回一个计算后的值。

以下是一些常见的CSS函数：

1. `rgb()`、`rgba()`：用于设置颜色值，接受红、绿、蓝和可选的透明度参数。例如：`color: rgb(255, 0, 0)`。
2. `hsl()`、`hsla()`：用于设置颜色值，接受色相、饱和度、亮度和可选的透明度参数。例如：`background-color: hsl(120, 100%, 50%)`。
3. `calc()`：用于执行数学计算，可以在属性值中进行加减乘除运算。例如：`width: calc(100% - 20px)`。
4. `url()`：用于引用外部资源，如图像、字体等。例如：`background-image: url('image.jpg')`。
5. `var()`：用于引用自定义属性（CSS变量）的值。例如：`color: var(--primary-color)`。
6. `linear-gradient()`、`radial-gradient()`：用于创建线性渐变或径向渐变的背景图像。例如：`background-image: linear-gradient(red, yellow)`。
7. `transform()`：用于对元素进行变换，如旋转、缩放、平移等。例如：`transform: rotate(45deg)`。
8. `font-family()`：用于设置字体系列，指定首选字体和备用字体。例如：`font-family: Arial, sans-serif`。
9. `attr()`：用于获取HTML元素的属性值，并将其应用于CSS样式中。例如：`content: attr(data-text)`。
10. `min()`、`max()`：用于选择最小或最大值。可以用于设置宽度、高度等属性。例如：`width: min(300px, 100%)`。

这只是一小部分常见的CSS函数，实际上还有许多其他的CSS函数可以用于不同的目的，如动画、过渡、滤镜效果等。使用CSS函数可以增强样式表的灵活性和功能性，使得开发者可以更精确地控制元素的样式和行为。