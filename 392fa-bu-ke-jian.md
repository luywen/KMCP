  
@font-face{  
font-family:"Times New Roman";  
}  
  
@font-face{  
font-family:"宋体";  
}  
  
@font-face{  
font-family:"等线";  
}  
  
@font-face{  
font-family:"楷体";  
}  
  
@font-face{  
font-family:"Arial";  
}  
  
p.MsoNormal{  
mso-style-name:正文;  
mso-style-parent:"";  
margin:0pt;  
margin-bottom:.0001pt;  
mso-pagination:none;  
text-align:justify;  
text-justify:inter-ideograph;  
font-family:等线;  
mso-bidi-font-family:'Times New Roman';  
font-size:10.5000pt;  
mso-font-kerning:1.0000pt;  
}  
  
p.p{  
mso-style-name:"普通\\(网站\\)";  
mso-style-noshow:yes;  
margin-top:5.0000pt;  
margin-bottom:5.0000pt;  
mso-margin-top-alt:auto;  
mso-margin-bottom-alt:auto;  
mso-pagination:widow-orphan;  
text-align:left;  
font-family:宋体;  
font-size:12.0000pt;  
}  
  
span.msoIns{  
mso-style-type:export-only;  
mso-style-name:"";  
text-decoration:underline;  
text-underline:single;  
color:blue;  
}  
  
span.msoDel{  
mso-style-type:export-only;  
mso-style-name:"";  
text-decoration:line-through;  
color:red;  
}  
@page{mso-page-border-surround-header:no;  
	mso-page-border-surround-footer:no;}@page Section0{  
}  
div.Section0{page:Section0;}

**3.9.2发布课件**

利用“打包”功能发布

　　这是最常用的一种方法，适合发布具有以下特点的课件：

1.有外部链接的影视文件或声音文件。

2.需要嵌入TrueType字体。

3.打算在尚未安装PowerPoint的计算机上运行。

　　在操作时，只需单击“文件”菜单下的“打包”命令，根据提示进行操作即可。打包后会生成Pngsetup.exe和Preso.ppz两个文件\(其中Pngsetup.exe为安装文件，Preso.ppz是一个压缩文件，它包含了演示文稿和外部链接文件\)。

　　此方法的不足之处在于：

1.打包需要一定的时间。

2.若要播放打包的课件，必须首先运行Pngsetup.exe将其解包，不能直接预览。

3.如果打包后又对课件做了修改，则必须运行“打包向导”重新打包。

　　所有内容放在同一目录下

　　我们以课件《National flag》为例，首先设置《National flag》文件夹，把PowerPoint课件链接的影视文件和声音文件都放进去，发布时只需拷贝《National flag》文件夹即可。因为在PowerPoint放映过程中，播放外部链接的影视文件或声音文件时，先会按照插入时的路径去找，如果找不到，则会自动播放演示文稿所在目录中的同名文件，如果演示文稿所在目录中也找不到文件，则就不能播放此外部链接文件了。

　　此方法适合发布具有以下特点的课件：

1.有外部链接的影视文件或声音文件.

2.不需要嵌入TrueType字体。

　　此方法最大的优点在于刻录成光盘后无需解包就可直接运行了，也就不需要用WinRAR来协助发布了，很方便。

　　发布调用外部程序的课件

　　如果设置了单击某个对象时就运行外部程序\(如Flash动画\)，发布课件时，使用“打包”命令也无济于事。怎么办呢?首先将D:My Documentsscreen.exe\(需要运行的程序的完整路径\)拷贝到PowerPoint演示文稿所在目录中，然后在“动作设置”窗口\(如图2\)中将“运动程序”中的路径删掉，只留下程序文件名“screen.exe”。发布时只需拷贝演示文稿所在目录就可以了。

　　以上是本人总结的PowerPoint课件发布的方法，大家可以根据课件特点，灵活地选择发布方法。另外，需要提醒大家注意的是：我们在用PowerPoint制作课件时，最好将要插入的外部链接文件先拷贝到演示文稿所在目录中，然后再插入，这样发布时只需拷贝演示文稿所在目录即可，既提高了效率，又不必担心“漏掉”文件。

