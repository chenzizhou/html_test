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

flex布局  弹性布局
让父盒子里面的元素变成行内块元素



异步请求
1、用第三方插件，axios构造函数 对XMLHttpRequest的封装
axios（{
url：'请求地址'，
method:'请求方法（put、delete、get、post）'，
params：'查询参数和get配和使用',
data:'请求体和post配合使用'
}）.then((result)=>{
//回调函数，处理响应,返回结果是对象
})

2、浏览器自带对象XMLHttpRequest构造函数
//创建XMLHttpRequest对象
xhr=new XMLHttpRequest()
//2、配置请求方法和请求url地址
xhr.open('请求方法'，'url')
//3、监听loadend事件，接受响应结果
xhr.addEventListener('loadend',()=.{
//返回结果是json字符串
console.log(xhr.response)
JSON.parse(xhr.response)
})
//发送请求
xhr.send()  
xhr.send(请求体)

