# BitmapFontMaker
BitmapFontMaker is use to create bitmap font,i used BMFont ever,but it is hard to use,so i write BitmapFontMaker.

BitmapFontMaker是用来制作图片字的工具，之前我一直使用BMFont，但是项目里的小伙伴都感觉它很麻烦，所以自己写了一个。

# 使用简介
首先 准备图片，图片命名必须是你在代码里用来作为这个图片字标志的字符。

比如 图片字是1，那么就用1。

如果图片字是汉字，比如暴击、那么你可以选择一个特殊字符比如 # 来命名图片，这样你在文本框里输入 # ，就显示的暴击这张图。

![Image](https://github.com/ThisisGame/BitmapFontMaker/blob/master/BitmapFontMaker/Doc/4.png)

打开BitmapFontmaker。

![Image](https://github.com/ThisisGame/BitmapFontMaker/blob/master/BitmapFontMaker/Doc/1.png)
 
 
上面的一块空白是显示选中的图片路径的，没什么用。
 
然后 选择打包图片的尺寸。
 
最后点击按钮，打开文件选择框，选中需要打包的图片，就可以了。

![Image](https://github.com/ThisisGame/BitmapFontMaker/blob/master/BitmapFontMaker/Doc/5.png)
 

打包好的图片以及fnt文件，存放在图片目录。


![Image](https://github.com/ThisisGame/BitmapFontMaker/blob/master/BitmapFontMaker/Doc/6.png)
 
拷贝到Unity 工程中，在NGUI中可以直接使用了。
 
如果图片的命名不规范，那么就会出现错误提示。

![Image](https://github.com/ThisisGame/BitmapFontMaker/blob/master/BitmapFontMaker/Doc/3.png)

![Image](https://github.com/ThisisGame/BitmapFontMaker/blob/master/BitmapFontMaker/Doc/2.png)
