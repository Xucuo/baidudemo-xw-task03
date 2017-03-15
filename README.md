遇到的问题：
一、子类元素脱离标准文档流后，父类元素会塌陷？
解决方法就是清楚浮动：
1：overflow：hidden || overflow :auto
2:隔墙法: <div style = "clear: both;"> </div>>
3:父类元素 一起浮动

二、中间栏怎么自适应宽度？
1：左右浮动，中间用margin撑开宽度
2:左右浮动，中间主体在HTML中放最后，

