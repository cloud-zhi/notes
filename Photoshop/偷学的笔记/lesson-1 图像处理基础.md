#lesson-1 图像处理基础

##位图和矢量图  

- 位图：由像素点构成的图像。像素点越多，相片品质越高。常见的格式有gif,png,jpg,psd等---不同的的代表不同编码格式。（ps就是用来处理位图的）**支持真色彩，可达256的三次方种色彩。**

- 矢量图：用直线和曲线来描述图形，没有分辨率的概念。（设计图纸）。通过数学公式计算获得，放大不会失真，不支持真色彩。用来图案设计（logo等）和文字设计（不同字体）。常见格式：ai,cdr,col等。（ps搞不了矢量图，会自动转换为位图）。

  **例子：**矢量图

  ![mark](http://qiniu.wind-zhou.com/blog/20201012/3Gfb8uTeSjNI.png?imageslim)

  



![mark](http://qiniu.wind-zhou.com/blog/20201012/NPEK7jKuvLRs.png?imageslim)



## 分辨率

概念：分辨率可分为显示分辨率和图片分辨率两种。

- 显示分辨率：表示屏幕图像的精密度，指的是显示器能显示的像素多少。主流电脑为1920*1680。**注：像素点的大小会根据电脑屏幕的大小调节的。**
- 图像分辨率：单位英寸中包含的像素点数（可以理解为像素密度）。

如果图片的像素大于显示器的极限分辨率会造成图片显示不完全。

**基本常识：**

照片分辨率：300ppi（达到这个像素就可以被洗出来）

网络照片：72ppi（**工作常用**） 

注：这里的网络照片的72ppi是在网络上**100%显示**时（就是在网络屏幕上也是等于一英寸大小时）的像素点数。

当网络图片或网站缩放时，像素点会相应的变小或放大。假如缩小照片，照片的像素点会变小，这时屏幕中的 一

个像素点会存放更多的像素点。

**关于手机上访问网站有时显示不完全的原因**：设计网站时可能一个像素点在手机上需要多个像素显示。