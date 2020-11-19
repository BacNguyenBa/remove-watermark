# n2n-watermark-remove
基于noise2noise修改的深度学习去水印项目。原作者项目链接https://github.com/yu4u/noise2noise

使用详细说明
https://www.zhihu.com/question/333086833/answer/841650555

视频演示 https://www.bilibili.com/video/av67886721

传统的图片去水印方法虽然效率高，但是对细节破坏的比较严重。去水印说简单也简单，说难也难。有的水印用修复图章几秒钟搞定，有的水印要一两个钟头还不一定能搞定。

一些细节不是很丰富的图片，可以通过photoshop等图像处理软件进行临近像素填充，掩盖水印部分，可以达到接近完美的效果。
(https://pic2.zhimg.com/v2-37061814ffd73b13b3be8b1cb816c8ab_r.jpg)![nyyyJsI.png]


去水印效果
这里是 1050ti 训练 9 小时的效果，可能有些不干净，理论上训练 20 小时以上就可以达到基本可用程度 （左边是原图，右边是去水印图，） ![nNIGQA.png](https://s2.ax1x.com/2019/09/10/nNIGQA.png)![nNIUdf.png](https://s2.ax1x.com/2019/09/10/nNIUdf.png)![nNINeP.png](https://s2.ax1x.com/2019/09/10/nNINeP.png)![nNIYLt.png](https://s2.ax1x.com/2019/09/10/nNIYLt.png)![nNIJsI.png](https://s2.ax1x.com/2019/09/10/nNIJsI.png)![nNIao8.png](https://s2.ax1x.com/2019/09/10/nNIao8.png)![nNIwFS.png](https://s2.ax1x.com/2019/09/10/nNIwFS.png)![nNI0Jg.png](https://s2.ax1x.com/2019/09/10/nNI0Jg.png)![nNIBWQ.png](https://s2.ax1x.com/2019/09/10/nNIBWQ.png)![nNIDzj.png](https://s2.ax1x.com/2019/09/10/nNIDzj.png)

其效果好过 photoshop 等专业级软件处理。

![](https://pic4.zhimg.com/v2-f2996de63636a0c5ee97c6ff5218ed7f_b.png)
