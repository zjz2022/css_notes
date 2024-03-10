CSS Less是一种CSS预处理器，它扩展了原始CSS的功能，使得编写CSS样式更加简洁和可维护。Less使用类似于CSS的语法，并引入了一些额外的功能和概念。

下面是一些常用的CSS Less语法：

1. 变量定义：

   

   

   ```css
   @variable-name: value;
   ```

   在Less中，你可以使用`@`符号定义变量，并给它赋一个值。这样可以方便地重用和管理样式中的值。

2. 嵌套规则：

   

   ```css
   .parent {
     property: value;
     .child {
       property: value;
     }
   }
   ```

   Less允许你在选择器中嵌套其他选择器，以便更清晰地组织样式规则。

3. 引用变量：

   

   ```css
   .element {
     property: @variable-name;
   }
   ```

   你可以使用变量来引用样式规则中的值，这样可以更方便地修改和管理样式。

4. 运算符：

   

   

   ```css
   @width: 100px;
   .element {
     width: @width + 20px;
   }
   ```

   Less支持数学运算符，你可以在样式中使用加减乘除等运算来计算属性的值。

5. 混合器（Mixin）：

   

   

   ```less
   .border-radius(@radius) {
     border-radius: @radius;
     -webkit-border-radius: @radius;
     -moz-border-radius: @radius;
   }
   
   .element {
     .border-radius(5px);
   }
   ```

   混合器允许你定义一组样式规则，并在需要时将其混合到其他选择器中。这样可以避免重复编写相同的样式。

6. 导入文件：

   

   ```css
   @import "styles.less";
   ```

   使用`@import`指令可以导入其他Less文件，以便在当前文件中使用导入文件中定义的样式。

7. 注释：

   

   ```css
   // 单行注释
   
   /*
   多行注释
   */
   ```

   Less支持单行注释(`//`)和多行注释(`/* */`)，可以用于注释代码和提供说明。

这些只是Less的一些基本语法示例。Less还提供了许多其他功能，例如条件语句、循环、颜色计算等。你可以查阅Less的官方文档以获取更详细的信息和更多的语法选项。

