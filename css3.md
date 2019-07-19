# <center> css3 </center>
### 边框阴影
box-shadow:阴影x轴的长度、阴影Y轴的长度、阴影的模糊半径、阴影的颜色
### 圆角边框
border-radius:左上、右上、右下、左下
### 边框图片
border-image:图片路径、剪裁位置(四个值：上右下左)、重复性
### 轮廓
outline-offset：距边框外距离
outline：轮廓
### 形变属性
1. 旋转：rotate(度数/单位：deg)
2. 缩放：scale(比例)
3. 位移：translate(x轴，y轴)
4. 过渡：transition(过渡属性、过渡时间、过渡函数、延长时间)
过渡函数：这个函数可以设置过渡效果是以怎样的方式运动。例：linear：运输运动
5. 倾斜：skew(x轴，y轴/单位deg)
6. 2D结合：transform:matrix(1a,b,c,1d,e,f);
(1).平移只和e跟f有关系，e对应x轴平移，f对应y轴平移
(2).缩放只和a跟d有关系。a对应x轴的缩放，d对应y轴的缩放 
(3).旋转:transform:matrix(cos,sin,-sin,cos ,0,0)
### 动画
1. 定义动画:@keyframes(动画名称)
2. 调用动画：animation(动画名称、动画时间、动画函数、延长时间)
3. 动画播放次数：animation-iteration-count：(infinite：循环)
4. 动画停止：animation-play-state:(paused:暂停)
### 背景
1. 背景图像的绘制区域:background-clip
三个值：
(1). border-box(为背景剪裁到边框盒{边框、内边距、内容都显示背景图片})
(2). padding-box(为背景剪裁到内边距框{内边距、内容都显示背景图片})
(3). content-box(为背景剪裁到内容框{仅内容显示背景图片})
2. 背景图片的定位区域：background-origin
设置元素背景图片的起始位置，其指定background-position属性的相对位置
### 文本
1. 文字阴影：text-shadow(可加多个阴影用逗号隔开)
三个值：水平阴影大小、垂直阴影大小、模糊度
2. 设置字符间距:letter-spacing
3. 自动换行：
(1).word-wrap:break-word;将长单词拆分
(2)work-break:break-all;比上一个拆分更彻底
(3)word-break:keep-all;在半角、空格或连字符处换行