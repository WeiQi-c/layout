# layout

### 前端布局面试题

   ##### 三栏布局
   
           左右固定中间自适应
           
           上下固定中间自适应
           
   #### 两栏布局
   
           上栏固定下栏自适应
           
           左栏固定右栏自适应

#### Grid布局
**display：grid 则该容器是一个块级元素**

**display: inline-grid 则容器元素为行内元素**

1.grid-template-columns 属性和 grid-template-rows 属性

grid-template-columns 属性设置列宽

grid-template-rows 属性设置行高

repeat() 函数：可以简化重复的值

auto-fill 关键字：表示自动填充，让一行（或者一列）中尽可能的容纳更多的单元格

fr 关键字： fr 单位代表网格容器中可用空间的一等份

minmax() 函数： 给网格元素一个最小和最大的尺寸

auto 关键字：由浏览器决定长度，自适应

2.grid-row-gap 属性、grid-column-gap 属性分别设置行间距和列间距。**grid-gap 属性是两者的简写形式。**
