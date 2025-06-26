# html_test
导航专业写法 nav>li>a
行内元素设置宽高，样式需添加display
文字垂直高度设置 line-height
文字颜色设置 color
a标签下划线去除 text-decoration：none

清除浮动
清除浮动带来的影响
父子级标签，子级浮动，父级没有高度，后面的标准流盒子会受影响


清除浮动的方法
1、直接设置父元素搞度
2、给添加的块级元素设置clear：both

class属性值 clearfic
3、单伪元素清除法

.clearfic::after{
cibtebtL'';
display:block;
clear:both;
height:0;
visibility:hidden;
}

transparent：透明
input焦点框取消：
outline：none

设置placeholder样式：
input::placeholder{
}

css精灵：
通过背景图+偏移对一张图片进行局部显示，一张图片解决多张图片下载

字体图标：
https://www.iconfont.cn/
