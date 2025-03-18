弹性子元素通常在弹性盒子内一行显示。默认情况每个容器只有一行
https://www.runoob.com/try/try.php?filename=trycss3_flexbox_flexline
如果我们设置 direction 属性为 rtl (right-to-left),弹性子元素的排列方式也会改变，页面布局也跟着改变
flex-direction的值有:

    row：横向从左到右排列（左对齐），默认的排列方式。
    row-reverse：反转横向排列（右对齐，从后往前排，最后一项排在最前面。
    column：纵向排列。
    column-reverse：反转纵向排列，从后往前排，最后一项排在最上面
https://www.runoob.com/try/try.php?filename=trycss3_flexbox_direction_column

CSS3 弹性盒子属性

下表列出了在弹性盒子中常用到的属性:
属性 	描述
display 	指定 HTML 元素盒子类型。
flex-direction 	指定了弹性容器中子元素的排列方式
justify-content 	设置弹性盒子元素在主轴（横轴）方向上的对齐方式。
align-items 	设置弹性盒子元素在侧轴（纵轴）方向上的对齐方式。
flex-wrap 	设置弹性盒子的子元素超出父容器时是否换行。
align-content 	修改 flex-wrap 属性的行为，类似 align-items, 但不是设置子元素对齐，而是设置行对齐
flex-flow 	flex-direction 和 flex-wrap 的简写
order 	设置弹性盒子的子元素排列顺序。
align-self 	在弹性子元素上使用。覆盖容器的 align-items 属性。
flex 	设置弹性盒子的子元素如何分配空间。


    网格布局 https://www.runoob.com/css3/css-grid.html
      grid-template-columns: auto auto auto auto;
  grid-template-rows: 100px 300px;
  https://www.runoob.com/try/try.php?filename=trycss_grid-template-rows
4等分
    grid-template-columns: 1fr 1fr 1fr 1fr;
    https://www.runoob.com/try/try.php?filename=trycss_grid-template-rows-fr
    


img {
    display: block;
    margin: auto;
    width: 40%;
}
<p>要让图片居中对齐, 可以使用 margin: auto; 并将它放到块元素中：</p>

<img src="https://static.jyshare.com/images/mix/paris.jpg" alt="Paris" style="width:40%">

