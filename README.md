### flex-direction 指定主轴方向，flex元素排列的顺序方向： 
- row 水平从左到右为主轴方向,默认值；
- row-reverse 水平从右到左为主轴方向；
- column 垂直从上到下为主轴方向；
- column-reverse 垂直从下往上为主轴方向；
**注意：**
如果存在多行flex元素，每一行的flex排列顺序分别按照这个规则来填充，比如：1、2、3、4、5,6、7、8、9、10两行，如果是row-reverse:654321,109876;

### flex-wrap 指定换行方式 ：
- nowrap 不换行，默认值；
- wrap 正向换行，如：1/2/3/4/5，6/7/8/9/10；正向排序就是1/2/3/4/5，6/7/8/9/10；
- wrap-reverse 反向换行，如：1/2/3/4/5，6/7/8/9/10；反向排序就是6/7/8/9/10，1/2/3/4/5；

### flex-flow flex-direction和flex-wrap合并属性 默认值为row nowrap。

### justify-content 属性定义了元素在主轴的对齐方式：

- flex-start：主轴首端对齐；
- flex-end：主轴末端对齐；
- center：主轴方向居中对齐；
- space-around：主轴方向平均间隔对齐，该属性在处理视图列表自适应平铺时比较适用；
- space-between：主轴方向两端对齐,该属性在处理视图列表自适应平铺两边不留白的情况下比较合适；
- stretch：主轴方向，自动拉伸到最大；