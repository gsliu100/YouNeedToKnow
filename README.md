# YouNeedToKnow

> 工作学习中你那些技术点---持续更新......

### 1. css中的vertical-align
先上图，图片下方的留白怎么产生的？



先来了解一下网页中关于字体与行高的各种概念

一行中的基线与行内元素基线
行的基线为该行行高最高元素的基线，默认情况下行中的元素的基线与行的基线在同一水平线上。
如下：

为行中非决定行基线的元素（不是最高的那些元素）设定vertical-align值时，如：设定vertical-align：middle,则该元素的中线将与行的基线对齐（也就是与最高元素的基线对齐）。

当为最高元素（决定行基线的元素）设定该属性值时，如：vertical-align:middle;会将行的基线也改为元素的中线，并且元素中线将与行基线进行对齐。


设置元素的vertical-align值为top/bottom时会将元素的顶部与底部对齐所在行的等不与底部。值为text-top/text-bottom时会将元素与行字体的顶部与底部对齐。值为middle时会将元素的中线与行的基线对齐


默认情况下行中的元素的基线会与行的基线对齐（行基线已经解释过了）



