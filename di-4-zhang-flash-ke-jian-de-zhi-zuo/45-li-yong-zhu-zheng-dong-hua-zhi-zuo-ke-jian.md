  
@font-face{  
font-family:"Times New Roman";  
}  
  
@font-face{  
font-family:"宋体";  
}  
  
@font-face{  
font-family:"Calibri";  
}  
  
@font-face{  
font-family:"Arial";  
}  
  
@font-face{  
font-family:"黑体";  
}  
  
@list l0:level1{  
mso-level-start-at:3;  
mso-level-number-format:decimal;  
mso-level-suffix:tab;  
mso-level-text:"%1.";  
mso-level-tab-stop:15.6000pt;  
mso-level-number-position:left;  
margin-left:0.0000pt;  
text-indent:0.0000pt;  
font-family:'Times New Roman';}  
  
@list l1:level1{  
mso-level-start-at:3;  
mso-level-number-format:decimal;  
mso-level-suffix:tab;  
mso-level-text:"\(%1\)";  
mso-level-tab-stop:15.6000pt;  
mso-level-number-position:left;  
margin-left:0.0000pt;  
text-indent:0.0000pt;  
font-family:'Times New Roman';}  
  
@list l2:level1{  
mso-level-start-at:2;  
mso-level-number-format:decimal;  
mso-level-suffix:tab;  
mso-level-text:"\(%1\)";  
mso-level-tab-stop:15.6000pt;  
mso-level-number-position:left;  
margin-left:0.0000pt;  
text-indent:0.0000pt;  
font-family:'Times New Roman';}  
  
@list l3:level1{  
mso-level-start-at:3;  
mso-level-number-format:decimal;  
mso-level-suffix:tab;  
mso-level-text:"%1\)";  
mso-level-tab-stop:15.6000pt;  
mso-level-number-position:left;  
margin-left:0.0000pt;  
text-indent:0.0000pt;  
font-family:'Times New Roman';}  
  
p.MsoNormal{  
mso-style-name:正文;  
mso-style-parent:"";  
margin:0pt;  
margin-bottom:.0001pt;  
mso-pagination:none;  
text-align:justify;  
text-justify:inter-ideograph;  
font-family:Calibri;  
mso-fareast-font-family:宋体;  
mso-bidi-font-family:'Times New Roman';  
font-size:10.5000pt;  
mso-font-kerning:1.0000pt;  
}  
  
span.10{  
font-family:'Times New Roman';  
}  
  
span.15{  
font-family:'Times New Roman';  
font-style:italic;  
}  
  
p.p{  
mso-style-name:"普通\\(网站\\)";  
mso-margin-top-alt:auto;  
mso-margin-bottom-alt:auto;  
mso-pagination:none;  
text-align:left;  
font-family:Calibri;  
mso-fareast-font-family:宋体;  
mso-bidi-font-family:'Times New Roman';  
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
margin-top:72.0000pt;  
margin-bottom:72.0000pt;  
margin-left:90.0000pt;  
margin-right:90.0000pt;  
size:595.3000pt 841.9000pt;  
layout-grid:15.6000pt;  
}  
div.Section0{page:Section0;}

**4.4 Flash逐帧动画**

        逐帧动画是一种常见的动画形式\(Frame By Frame\)，其原理是在"连续的关键帧"中分解动画动作，也就是在时间轴的每帧上逐帧绘制不同的内容，使其连续播放而成动画。逐帧动画具有非常大的灵活性，几乎可以表现任何想表现的内容。它类似于电影的播放模式，很适合表演细腻的动画，例如人物走路、说话等。

**学习目的**

本节你将学习掌握以下内容：

        逐帧动画的制作方法

  
@font-face{  
font-family:"Times New Roman";  
}  
  
@font-face{  
font-family:"宋体";  
}  
  
@font-face{  
font-family:"Calibri";  
}  
  
@font-face{  
font-family:"Arial";  
}  
  
@font-face{  
font-family:"黑体";  
}  
  
@list l0:level1{  
mso-level-start-at:3;  
mso-level-number-format:decimal;  
mso-level-suffix:tab;  
mso-level-text:"%1.";  
mso-level-tab-stop:15.6000pt;  
mso-level-number-position:left;  
margin-left:0.0000pt;  
text-indent:0.0000pt;  
font-family:'Times New Roman';}  
  
@list l1:level1{  
mso-level-start-at:3;  
mso-level-number-format:decimal;  
mso-level-suffix:tab;  
mso-level-text:"\(%1\)";  
mso-level-tab-stop:15.6000pt;  
mso-level-number-position:left;  
margin-left:0.0000pt;  
text-indent:0.0000pt;  
font-family:'Times New Roman';}  
  
@list l2:level1{  
mso-level-start-at:2;  
mso-level-number-format:decimal;  
mso-level-suffix:tab;  
mso-level-text:"\(%1\)";  
mso-level-tab-stop:15.6000pt;  
mso-level-number-position:left;  
margin-left:0.0000pt;  
text-indent:0.0000pt;  
font-family:'Times New Roman';}  
  
@list l3:level1{  
mso-level-start-at:3;  
mso-level-number-format:decimal;  
mso-level-suffix:tab;  
mso-level-text:"%1\)";  
mso-level-tab-stop:15.6000pt;  
mso-level-number-position:left;  
margin-left:0.0000pt;  
text-indent:0.0000pt;  
font-family:'Times New Roman';}  
  
p.MsoNormal{  
mso-style-name:正文;  
mso-style-parent:"";  
margin:0pt;  
margin-bottom:.0001pt;  
mso-pagination:none;  
text-align:justify;  
text-justify:inter-ideograph;  
font-family:Calibri;  
mso-fareast-font-family:宋体;  
mso-bidi-font-family:'Times New Roman';  
font-size:10.5000pt;  
mso-font-kerning:1.0000pt;  
}  
  
span.10{  
font-family:'Times New Roman';  
}  
  
span.15{  
font-family:'Times New Roman';  
font-style:italic;  
}  
  
p.p{  
mso-style-name:"普通\\(网站\\)";  
mso-margin-top-alt:auto;  
mso-margin-bottom-alt:auto;  
mso-pagination:none;  
text-align:left;  
font-family:Calibri;  
mso-fareast-font-family:宋体;  
mso-bidi-font-family:'Times New Roman';  
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
margin-top:72.0000pt;  
margin-bottom:72.0000pt;  
margin-left:90.0000pt;  
margin-right:90.0000pt;  
size:595.3000pt 841.9000pt;  
layout-grid:15.6000pt;  
}  
div.Section0{page:Section0;}

**4.4 Flash逐帧动画**

逐帧动画是一种常见的动画形式\(Frame By Frame\)，其原理是在"连续的关键帧"中分解动画动作，也就是在时间轴的每帧上逐帧绘制不同的内容，使其连续播放而成动画。逐帧动画具有非常大的灵活性，几乎可以表现任何想表现的内容。它类似于电影的播放模式，很适合表演细腻的动画，例如人物走路、说话等。

**学习目的**

本节你将学习掌握以下内容：

逐帧动画的制作方法

插入帧与删除帧

【绘图纸外观】按钮![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF385.tmp.png)的使用方法

【对齐面板】的使用方法



**1.相关概念**

\(1\).空帧

如图4-4-1，空帧在时间轴上就是一个个方格，表示图层中动画的结束。

![](/assets/图片1.png)

**图4-4-1 空帧**

\(2\).关键帧

关键帧是制作课件时非常重要的帧，是用来定义动画变化、状态更改的帧。Flash会根据用户正确定义的关键帧，自动完成两个关键帧之间的一些指定的过渡效果。所以只有正确定义了关键帧，才能实现动画制作中的一些由电脑自动完成的过程。如图4-4-2都是关键帧。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF397.tmp.jpg)

**图4-4-2 关键帧**

\(3\).普通帧

普通帧也称为静态帧，用于延长前面一帧的状态，在关键帧后面的普通帧为灰色，在空白关键帧后的普通帧为白色，如图4-4-3。

![](/assets/图片3.png)

**图4-4-3 普通帧**

\(4\).帧的速度

帧的速度是指动画播放的速度，帧速的单位是FPS（帧/秒），即每秒钟播放的帧数。帧速决定了动画播放的连贯性，帧速太慢，就会明显感觉动画播放的停顿；帧数太快，就会忽略动画的部分细节。



本案例是幼儿园上英语how is the weather的演示课件，它通过逐帧动画演示了几种天气的特点，充分显示了使用flash动画模拟课件再现生活场景的无穷魅力。



**2.制作逐帧动画**



1）文字逐帧动画

逐帧动画适合制作相邻关键帧中对象变化不大的动画。利用flash中的逐帧动画，可以让文字逐个以打字的形式显示出来，此类动画可用于增强课件中文字显示的动感效果。

\(1\)**.**【新建flash文件】打开flash软件，新建一个flash文件、按图 所示操作，设置舞台尺寸为 550×400像素，背景色为白色，其他参数保持默认值。

\(2\).【添加背景图片】新建图层，双击图层名称，将其图层名称修改为【背景图片】，执行【文件】\|【导入到库】，将图片放置在舞台合适位置，如图4-4-4和4-4-5。将该图层的帧延续到第100帧（F5）。

![](/assets/图片4.png)

**图4-4-4新建图层图4-4-5修改名**

\(3\).【新建图层【学前英语】 】新建图层，双击图层名称，将其图层名称修改为【学前英语】。

![](/assets/图片47.png)

\(4\).【输入标题】打开半成品课件“How is the weather”。按图4.4-2-3所示操作，在【学前英语】图层的第25帧添加关键帧（F6）输入文字【学前英语】，并设置字体格式，如图4-4-6和4-4-7。

![](/assets/图片6.png)

**图4-4-6输入文字**

![](/assets/图片7.png)

**图4-4-7颜色面板**

\(5\).【输入How is the weather】新建图层，改名为【How is the weather】，在该图层中我们将实现动态文字的效果，即内容How is the weather按单词顺序依次出现。

\(6\).【延续帧】将所有图层的帧利用F5设置帧延续的第100帧，在图层【How is the weather】的第35帧设置关键帧，如图4-4-8。

![](/assets/图片8.png)

**图4-4-8延续帧**

\(7\).【制作动态文字效果】

①【添加文本框**】**按图所示操作，在“How is the weather ”图层的第35帧上绘制一个文本框，如图4-4-9所示。

![](/assets/图片9.png)

**图4-4-9添加文本框**

② 【输入第一个单词】  按图4-4-10,4-4-11,4-4-12所示操作，在文本框内输入第一个单词“How”,修改字体属性，在对齐面板中选择水平中齐。

![](/assets/图片10.png)

**图4-4-10修改文字属性**

![](/assets/图片11.png)

**图4-4-11 水平中齐**

![](/assets/图片12.png)

**图4-4-12 输入【How】**

③【输入第二个字**】**在“How is the weather”图层的第40帧添加一个关键帧，并在文本框中输入第二个单词“is”，在对齐面板中选择水平中齐，如图4-4-13。

![](/assets/图片13.png)

**图4-4-13 输入【is】**

④【输入其他单词】  重复步骤6，每添加一个关键帧，在文本框内添加一个单词，用对齐面板将其放在适当位置，最终时间轴和舞台效果如图4-4-14和4-4-15。

![](/assets/图片14.png)

**图4-4-14舞台效果**

![](/assets/图片15.png)

**图4-4-15时间轴**

⑤**【**多帧调整**】**单击【时间轴】面板下方的【绘图纸外观】按钮![](/assets/图片33.png)，将写有单词的几帧内容放置在合适位置，如图4-4-16。

![](/assets/图片16.png)

**图4-4-16绘图纸外观下的舞台**

⑥【取消多帧查看】单击【绘图纸外观】按钮![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF462.tmp.png)取消其多帧查看效果。









2）制作图形动画



看了我们的半成品课件，我们还会发现，我们cloudy图形动画没有完成，现在我们就来完成这部分课件。

\(1\).【新建图层】  新建图层【cloudy】，放在raining图层和windy图层之中。

\(2\).【新建元件】执行【插入】\|【新建元件】命令，在弹出的对话框中填写元件名称【cloudy】，类型【影片剪辑】元件,如图4-4-17。

![](/assets/图片17.png)

**图4-4-17新建元件**



\(3\).【修改图层名称】  在库中打开【cloudy】元件，将元件中图层一改名为【cloudy】。

\(4\).【进行绘图 】

①【画椭圆】在【cloudy】图层的第一帧设置关键帧，在舞台上用椭圆工具绘制一个没有填充颜色的椭圆，如图4-4-18和4-4-19。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF475.tmp.jpg)

**图4-4-18椭圆工具图4-4-19画椭圆**

②【椭圆组合】在第二帧设置关键帧，复制之前绘制的椭圆，将两个椭圆接在一起，重复几次，如图4-4-20。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF485.tmp.jpg)

**图4-4-20 椭圆组合**

③【删线】删除内部多余的线条，如图4-4-21。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF496.tmp.jpg)

**图4-4-21 云**

（4）【绘制表情】添加关键帧，用【线条工具】绘制表情，每帧绘制不同的部位，最终绘制的图以及时间轴如图4-4-22,4-4-23和4-4-24所示。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF497.tmp.jpg)![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF4A8.tmp.jpg)

**图4-4-22线条工具属性图4-4-23舞台效果**

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF4B8.tmp.jpg)

**图4-4-24时间轴**



（5）【被遮住的太阳】在【cloudy】元件中新建图层【被遮住的太阳】,将新图层放在【cloudy】图层下方，单击【cloudy】图层在【时间轴】面板小黄锁下方的黑点，对此图层进行加锁，如图4-4-25所示。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF4B9.tmp.jpg)

**图4-4-25锁定**

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF4CA.tmp.jpg)

（6）【画太阳】在【被遮住的太阳】的图层第15帧设置关键帧，在舞台上利用椭圆工具，按住ctrl+shift画太阳，利用线条工具画太阳光芒，如图4-4-26。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF4CB.tmp.jpg)

**图4-4-26 半成品**





（7）【添加颜色】添加颜色根据实际情况利用颜色面板和渐变变形工具为云与太阳逐帧添加颜色，如图4-4-27和4-4-28。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF4DB.tmp.jpg)

**图4-4-27颜色面板**

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF4EC.tmp.jpg)

**图4-4-28 cloudy成品**



3\)制作“音乐”图层



在“音乐”图层添加一些声音效果，让动态文字在出现时配上打字的声音，这样会使课件更生动。

\(1\).【添加图层】  在半成品课件中新建图层，并重新命名为“音乐”

\(2\).【添加声音】执行【文件】\|【导入到库】命令导入所要添加的音乐，单击“音乐”图层的第一帧，按图4-4-29所示操作，给图层添加声音效果。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF4ED.tmp.jpg)

**图4-4-29 导入音乐**

\(3\).【插入帧与删除多余的帧】现在可以按“Ctrl+Enter”测试一下动画效果，如果音乐与动画没有合拍，通过插入帧与删除多余帧来进行调整。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF4FE.tmp.jpg)\(4\).【保存并测试课件】  执行【控制】\|【测试影片】命令（快捷键Ctrl+Enter），观察动画效果，如果满意，执行【文件】\|【保存】命令，保存课件。



3.**功能详解**

在前面的动画中，我们利用实例讲解了【对齐面板】中的上对齐功能，还讲解了【绘画纸】里的【绘图纸外观】按钮![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF50E.tmp.png)的使用方法。下面详细的讲解一下【绘画纸】的功能、【对齐面板】的应用，并给大家归纳总结创建逐帧动画的方法。

\(1\)．【绘画纸】的功能

【绘画纸】是一个帮助定位和编辑动画的辅助功能，这个功能对制作逐帧动画特别有用。通常情况下，Flash在舞台中一次只能显示动画序列的单个帧。使用绘画纸功能后，你就可以在舞台中一次查看两个或多个帧了。

如图4-4-30所示，这是使用【绘画纸】功能后的场景，可以看出，当前帧中内容用全彩色显示，其它帧内容以半透明显示，它使我们看起来好像所有帧内容是画在一张半透明的绘图纸上，这些内容相互层叠在一起。当然，这时你只能编辑当前帧的内容。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF50F.tmp.jpg)

**图4-4-30同时显示多帧内容的变化**

【绘画纸】各个按钮的功能：

①![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF520.tmp.png)【绘图纸外观】按钮：按下此按钮后，在时间帧的上方，出现![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF521.tmp.png)绘图纸外观标记。拉动外观标记的两端，可以扩大或缩小显示范围。

②![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF531.tmp.png)【绘图纸外观轮廓】按钮：按下此按钮后，场景中显示各帧内容的轮廓线，填充色消失，特别适合观察对象轮廓，另外可以节省系统资源，加快显示过程。

③![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF532.tmp.png)【编辑多个帧】按钮：按下后可以显示全部帧内容，并且可以进行“多帧同时编辑”。

④![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF533.tmp.png)【修改绘图纸标记】按钮：按下后，弹出菜单，菜单中有以下选项：

A.【始终显示标记】选项：会在时间轴标题中显示绘图纸外观标记，无论绘图纸外观是否打开。

B.【锚定标记】选项：会将绘图纸外观标记锁定在它们在时间轴标题中的当前位置。通常情况下，绘图纸外观范围是和当前帧的指针以及绘图纸外观标记相关的。通过锚定绘图纸外观标记，可以防止它们随当前帧的指针移动。

C.【标记范围2】选项；会在当前帧的两边显示两个帧。

D.【标记范围5】选项；会在当前帧的两边显示五个帧。

E.【标记所有范围】选项；会在当前帧的两边显示全部帧。

\(2\)．【对齐面板】的应用

使用【对齐面板】，可以对编辑区中多个对像进行排列、分布、匹配大小、调整间隔等操作，使布局整齐美观，如图4-4-31所示。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF544.tmp.jpg)

**图4-4-31对齐面板**

【对齐面板】由排列对齐、分布对齐、匹配大小、间隔以及相对舞台同几部分组成：

①排列对齐（水平排列和垂直排列）

A.水平排列![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF545.tmp.png)：从左到右分边是水平方向的左对齐、左右居中对齐、右对齐。

B.垂直排列![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF556.tmp.png)：从左到右分边是垂直方向的上对齐、上下居中对齐、下对齐。

②分布对齐（水平分布和垂直分布）：

A.水平分布![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF557.tmp.png)：从左到右分别为垂直方向基于上边缘的分布、基于中心的分布、基于下边缘的分布。

B.垂直分布![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF567.tmp.png)：从左到右分别为水平方向基于左边缘的分布、基于中心的分布、基于右边缘的分布。

③匹配大小![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF568.tmp.png)：将一组对象的宽度、高度或两者调整为对象的最大尺寸。从左到右分别为水平对齐、垂直对齐、水平垂直对齐。

④间隔![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF579.tmp.png)：将一组对象在水平或垂直方向上按照等间距的方式排列。从左到右分别为水平间距的调整、垂直间距的调整。

⑤相对舞台![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF57A.tmp.png)：在默认状态时上述按钮的操作是对于对象本身的，单击此按钮后，则所做的操作是相对于舞台的。

pp��r�\]  
@font-face{  
font-family:"Times New Roman";  
}  
  
@font-face{  
font-family:"宋体";  
}  
  
@font-face{  
font-family:"Calibri";  
}  
  
@font-face{  
font-family:"Arial";  
}  
  
@font-face{  
font-family:"黑体";  
}  
  
@list l0:level1{  
mso-level-start-at:3;  
mso-level-number-format:decimal;  
mso-level-suffix:tab;  
mso-level-text:"%1.";  
mso-level-tab-stop:15.6000pt;  
mso-level-number-position:left;  
margin-left:0.0000pt;  
text-indent:0.0000pt;  
font-family:'Times New Roman';}  
  
@list l1:level1{  
mso-level-start-at:3;  
mso-level-number-format:decimal;  
mso-level-suffix:tab;  
mso-level-text:"\(%1\)";  
mso-level-tab-stop:15.6000pt;  
mso-level-number-position:left;  
margin-left:0.0000pt;  
text-indent:0.0000pt;  
font-family:'Times New Roman';}  
  
@list l2:level1{  
mso-level-start-at:2;  
mso-level-number-format:decimal;  
mso-level-suffix:tab;  
mso-level-text:"\(%1\)";  
mso-level-tab-stop:15.6000pt;  
mso-level-number-position:left;  
margin-left:0.0000pt;  
text-indent:0.0000pt;  
font-family:'Times New Roman';}  
  
@list l3:level1{  
mso-level-start-at:3;  
mso-level-number-format:decimal;  
mso-level-suffix:tab;  
mso-level-text:"%1\)";  
mso-level-tab-stop:15.6000pt;  
mso-level-number-position:left;  
margin-left:0.0000pt;  
text-indent:0.0000pt;  
font-family:'Times New Roman';}  
  
p.MsoNormal{  
mso-style-name:正文;  
mso-style-parent:"";  
margin:0pt;  
margin-bottom:.0001pt;  
mso-pagination:none;  
text-align:justify;  
text-justify:inter-ideograph;  
font-family:Calibri;  
mso-fareast-font-family:宋体;  
mso-bidi-font-family:'Times New Roman';  
font-size:10.5000pt;  
mso-font-kerning:1.0000pt;  
}  
  
span.10{  
font-family:'Times New Roman';  
}  
  
span.15{  
font-family:'Times New Roman';  
font-style:italic;  
}  
  
p.p{  
mso-style-name:"普通\\(网站\\)";  
mso-margin-top-alt:auto;  
mso-margin-bottom-alt:auto;  
mso-pagination:none;  
text-align:left;  
font-family:Calibri;  
mso-fareast-font-family:宋体;  
mso-bidi-font-family:'Times New Roman';  
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
margin-top:72.0000pt;  
margin-bottom:72.0000pt;  
margin-left:90.0000pt;  
margin-right:90.0000pt;  
size:595.3000pt 841.9000pt;  
layout-grid:15.6000pt;  
}  
div.Section0{page:Section0;}

**4.4 Flash逐帧动画**

  
@font-face{  
font-family:"Times New Roman";  
}  
  
@font-face{  
font-family:"宋体";  
}  
  
@font-face{  
font-family:"Calibri";  
}  
  
@font-face{  
font-family:"Arial";  
}  
  
@font-face{  
font-family:"黑体";  
}  
  
@list l0:level1{  
mso-level-start-at:3;  
mso-level-number-format:decimal;  
mso-level-suffix:tab;  
mso-level-text:"%1.";  
mso-level-tab-stop:15.6000pt;  
mso-level-number-position:left;  
margin-left:0.0000pt;  
text-indent:0.0000pt;  
font-family:'Times New Roman';}  
  
@list l1:level1{  
mso-level-start-at:3;  
mso-level-number-format:decimal;  
mso-level-suffix:tab;  
mso-level-text:"\(%1\)";  
mso-level-tab-stop:15.6000pt;  
mso-level-number-position:left;  
margin-left:0.0000pt;  
text-indent:0.0000pt;  
font-family:'Times New Roman';}  
  
@list l2:level1{  
mso-level-start-at:2;  
mso-level-number-format:decimal;  
mso-level-suffix:tab;  
mso-level-text:"\(%1\)";  
mso-level-tab-stop:15.6000pt;  
mso-level-number-position:left;  
margin-left:0.0000pt;  
text-indent:0.0000pt;  
font-family:'Times New Roman';}  
  
@list l3:level1{  
mso-level-start-at:3;  
mso-level-number-format:decimal;  
mso-level-suffix:tab;  
mso-level-text:"%1\)";  
mso-level-tab-stop:15.6000pt;  
mso-level-number-position:left;  
margin-left:0.0000pt;  
text-indent:0.0000pt;  
font-family:'Times New Roman';}  
  
p.MsoNormal{  
mso-style-name:正文;  
mso-style-parent:"";  
margin:0pt;  
margin-bottom:.0001pt;  
mso-pagination:none;  
text-align:justify;  
text-justify:inter-ideograph;  
font-family:Calibri;  
mso-fareast-font-family:宋体;  
mso-bidi-font-family:'Times New Roman';  
font-size:10.5000pt;  
mso-font-kerning:1.0000pt;  
}  
  
span.10{  
font-family:'Times New Roman';  
}  
  
span.15{  
font-family:'Times New Roman';  
font-style:italic;  
}  
  
p.p{  
mso-style-name:"普通\\(网站\\)";  
mso-margin-top-alt:auto;  
mso-margin-bottom-alt:auto;  
mso-pagination:none;  
text-align:left;  
font-family:Calibri;  
mso-fareast-font-family:宋体;  
mso-bidi-font-family:'Times New Roman';  
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
margin-top:72.0000pt;  
margin-bottom:72.0000pt;  
margin-left:90.0000pt;  
margin-right:90.0000pt;  
size:595.3000pt 841.9000pt;  
layout-grid:15.6000pt;  
}  
div.Section0{page:Section0;}

**4.4 Flash逐帧动画**

       逐帧动画是一种常见的动画形式\(Frame By Frame\)，其原理是在"连续的关键帧"中分解动画动作，也就是在时间轴的每帧上逐帧绘制不同的内容，使其连续播放而成动画。逐帧动画具有非常大的灵活性，几乎可以表现任何想表现的内容。它类似于电影的播放模式，很适合表演细腻的动画，例如人物走路、说话等。

**学习目的**

本节你将学习掌握以下内容：

        逐帧动画的制作方法

        插入帧与删除帧

        【绘图纸外观】按钮![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF385.tmp.png)的使用方法

        【对齐面板】的使用方法



**1.相关概念**

\(1\).空帧

        如图4-4-1，空帧在时间轴上就是一个个方格，表示图层中动画的结束。

                                                                                    ![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF396.tmp.jpg)

                                                                                                                   **图4-4-1 空帧**

\(2\).关键帧  

        关键帧是制作课件时非常重要的帧，是用来定义动画变化、状态更改的帧。Flash会根据用户正确定义的关键帧，自动完成两个关键帧之间的一些指定的过渡效果。所以只有正确定义了关键帧，才能实现动画制作中的一些由电脑自动完成的过程。如图4-4-2都是关键帧。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF397.tmp.jpg)

**图4-4-2 关键帧**

\(3\).普通帧

        普通帧也称为静态帧，用于延长前面一帧的状态，在关键帧后面的普通帧为灰色，在空白关键帧后的普通帧为白色，如图4-4-3。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF3A8.tmp.jpg)

**图4-4-3 普通帧**

\(4\).帧的速度

        帧的速度是指动画播放的速度，帧速的单位是FPS（帧/秒），即每秒钟播放的帧数。帧速决定了动画播放的连贯性，帧速太慢，就会明显感觉动画播放的停顿；帧数太快，就会忽略动画的部分细节。



        本案例是幼儿园上英语how is the weather的演示课件，它通过逐帧动画演示了几种天气的特点，充分显示了使用flash动画模拟课件再现生活场景的无穷魅力。



**2.制作逐帧动画**



1）文字逐帧动画

        逐帧动画适合制作相邻关键帧中对象变化不大的动画。利用flash中的逐帧动画，可以让文字逐个以打字的形式显示出来，此类动画可用于增强课件中文字显示的动感效果。

\(1\)**.**【新建flash文件】    打开flash软件，新建一个flash文件、按图 所示操作，设置舞台尺寸为 550×400像素，背景色为白色，其他参数保持默认值。

\(2\).【添加背景图片】    新建图层，双击图层名称，将其图层名称修改为【背景图片】，执行【文件】\|【导入到库】，将图片放置在舞台合适位置，如图4-4-4和4-4-5。将该图层的帧延续到第100帧（F5）。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF3B8.tmp.jpg)

**图4-4-4新建图层图4-4-5修改名称**

\(3\).【新建图层【学前英语】 】    新建图层，双击图层名称，将其图层名称修改为【学前英语】。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF3B9.tmp.jpg)



\(4\).【输入标题】    打开半成品课件“How is the weather”。按图4.4-2-3所示操作，在【学前英语】图层的第25帧添加关键帧（F6）输入文字【学前英语】，并设置字体格式，如图4-4-6和4-4-7。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF3CA.tmp.jpg)

**图4-4-6输入文字**

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF3CB.tmp.jpg)

**图4-4-7颜色面板**

\(5\).【输入How is the weather】    新建图层，改名为【How is the weather】，在该图层中我们将实现动态文字的效果，即内容How is the weather按单词顺序依次出现。

\(6\).【延续帧】    将所有图层的帧利用F5设置帧延续的第100帧，在图层【How is the weather】的第35帧设置关键帧，如图4-4-8。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF3DB.tmp.jpg)

**图4-4-8延续帧**

\(7\).【制作动态文字效果】

①【添加文本框**】    **按图所示操作，在“How is the weather ”图层的第35帧上绘制一个文本框，如图4-4-9所示。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF3EC.tmp.jpg)

**图4-4-9添加文本框**

② 【输入第一个单词】      按图4-4-10,4-4-11,4-4-12所示操作，在文本框内输入第一个单词“How”,修改字体属性，在对齐面板中选择水平中齐。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF3ED.tmp.jpg)

**图4-4-10修改文字属性**

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF3FE.tmp.jpg)

**图4-4-11 水平中齐**

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF40E.tmp.jpg)

**图4-4-12 输入【How】**

③【输入第二个字**】    **在“How is the weather”图层的第40帧添加一个关键帧，并在文本框中输入第二个单词“is”，在对齐面板中选择水平中齐，如图4-4-13。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF40F.tmp.jpg)

**图4-4-13 输入【is】**

④【输入其他单词】      重复步骤6，每添加一个关键帧，在文本框内添加一个单词，用对齐面板将其放在适当位置，最终时间轴和舞台效果如图4-4-14和4-4-15。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF420.tmp.jpg)

**图4-4-14舞台效果**

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF440.tmp.jpg)

**图4-4-15时间轴**

⑤**【**多帧调整**】    **单击【时间轴】面板下方的【绘图纸外观】按钮![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF451.tmp.jpg)，将写有单词的几帧内容放置在合适位置，如图4-4-16。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF452.tmp.jpg)

**图4-4-16绘图纸外观下的舞台**

⑥【取消多帧查看】    单击【绘图纸外观】按钮![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF462.tmp.png)取消其多帧查看效果。









2）制作图形动画



看了我们的半成品课件，我们还会发现，我们cloudy图形动画没有完成，现在我们就来完成这部分课件。

\(1\).【新建图层】    新建图层【cloudy】，放在raining图层和windy图层之中。

\(2\).【新建元件】    执行【插入】\|【新建元件】命令，在弹出的对话框中填写元件名称【cloudy】，类型【影片剪辑】元件,如图4-4-17。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF463.tmp.jpg)

**图4-4-17新建元件**



\(3\).【修改图层名称】    在库中打开【cloudy】元件，将元件中图层一改名为【cloudy】。

\(4\).【进行绘图 】

①【画椭圆】    在【cloudy】图层的第一帧设置关键帧，在舞台上用椭圆工具绘制一个没有填充颜色的椭圆，如图4-4-18和4-4-19。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF474.tmp.jpg)![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF475.tmp.jpg)

**图4-4-18椭圆工具图4-4-19画椭圆**

②【椭圆组合】    在第二帧设置关键帧，复制之前绘制的椭圆，将两个椭圆接在一起，重复几次，如图4-4-20。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF485.tmp.jpg)

**图4-4-20 椭圆组合**

③【删线】    删除内部多余的线条，如图4-4-21。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF496.tmp.jpg)

**图4-4-21 云**

（4）【绘制表情】    添加关键帧，用【线条工具】绘制表情，每帧绘制不同的部位，最终绘制的图以及时间轴如图4-4-22,4-4-23和4-4-24所示。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF497.tmp.jpg)![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF4A8.tmp.jpg)

**图4-4-22线条工具属性图4-4-23舞台效果**

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF4B8.tmp.jpg)

**图4-4-24时间轴**



（5）【被遮住的太阳】    在【cloudy】元件中新建图层【被遮住的太阳】,将新图层放在【cloudy】图层下方，单击【cloudy】图层在【时间轴】面板小黄锁下方的黑点，对此图层进行加锁，如图4-4-25所示。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF4B9.tmp.jpg)

**图4-4-25锁定**

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF4CA.tmp.jpg)

（6）【画太阳】    在【被遮住的太阳】的图层第15帧设置关键帧，在舞台上利用椭圆工具，按住ctrl+shift画太阳，利用线条工具画太阳光芒，如图4-4-26。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF4CB.tmp.jpg)

**图4-4-26 半成品**





（7）【添加颜色】    添加颜色根据实际情况利用颜色面板和渐变变形工具为云与太阳逐帧添加颜色，如图4-4-27和4-4-28。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF4DB.tmp.jpg)

**图4-4-27颜色面板**

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF4EC.tmp.jpg)

**图4-4-28 cloudy成品**



3\)制作“音乐”图层



在“音乐”图层添加一些声音效果，让动态文字在出现时配上打字的声音，这样会使课件更生动。

\(1\).【添加图层】    在半成品课件中新建图层，并重新命名为“音乐”

\(2\).【添加声音】    执行【文件】\|【导入到库】命令导入所要添加的音乐，单击“音乐”图层的第一帧，按图4-4-29所示操作，给图层添加声音效果。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF4ED.tmp.jpg)

**图4-4-29 导入音乐**

\(3\).【插入帧与删除多余的帧】    现在可以按“Ctrl+Enter”测试一下动画效果，如果音乐与动画没有合拍，通过插入帧与删除多余帧来进行调整。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF4FE.tmp.jpg)

\(4\).【保存并测试课件】     执行【控制】\|【测试影片】命令（快捷键Ctrl+Enter），观察动画效果，如果满意，执行【文件】\|【保存】命令，保存课件。



3.**功能详解**

        在前面的动画中，我们利用实例讲解了【对齐面板】中的上对齐功能，还讲解了【绘画纸】里的【绘图纸外观】按钮![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF50E.tmp.png)的使用方法。下面详细的讲解一下【绘画纸】的功能、【对齐面板】的应用，并给大家归纳总结创建逐帧动画的方法。

\(1\)．【绘画纸】的功能

        【绘画纸】是一个帮助定位和编辑动画的辅助功能，这个功能对制作逐帧动画特别有用。通常情况下，Flash在舞台中一次只能显示动画序列的单个帧。使用绘画纸功能后，你就可以在舞台中一次查看两个或多个帧了。

如图4-4-30所示，这是使用【绘画纸】功能后的场景，可以看出，当前帧中内容用全彩色显示，其它帧内容以半透明显示，它使我们看起来好像所有帧内容是画在一张半透明的绘图纸上，这些内容相互层叠在一起。当然，这时你只能编辑当前帧的内容。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF50F.tmp.jpg)

**图4-4-30同时显示多帧内容的变化**

【绘画纸】各个按钮的功能：

①![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF520.tmp.png)【绘图纸外观】按钮：按下此按钮后，在时间帧的上方，出现![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF521.tmp.png)绘图纸外观标记。拉动外观标记的两端，可以扩大或缩小显示范围。

②![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF531.tmp.png)【绘图纸外观轮廓】按钮：按下此按钮后，场景中显示各帧内容的轮廓线，填充色消失，特别适合观察对象轮廓，另外可以节省系统资源，加快显示过程。

③![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF532.tmp.png)【编辑多个帧】按钮：按下后可以显示全部帧内容，并且可以进行“多帧同时编辑”。

④![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF533.tmp.png)【修改绘图纸标记】按钮：按下后，弹出菜单，菜单中有以下选项：

A.【始终显示标记】选项：会在时间轴标题中显示绘图纸外观标记，无论绘图纸外观是否打开。

B.【锚定标记】选项：会将绘图纸外观标记锁定在它们在时间轴标题中的当前位置。通常情况下，绘图纸外观范围是和当前帧的指针以及绘图纸外观标记相关的。通过锚定绘图纸外观标记，可以防止它们随当前帧的指针移动。

C.【标记范围2】选项；会在当前帧的两边显示两个帧。

D.【标记范围5】选项；会在当前帧的两边显示五个帧。

E.【标记所有范围】选项；会在当前帧的两边显示全部帧。

\(2\)．【对齐面板】的应用

使用【对齐面板】，可以对编辑区中多个对像进行排列、分布、匹配大小、调整间隔等操作，使布局整齐美观，如图4-4-31所示。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF544.tmp.jpg)

**图4-4-31对齐面板**

【对齐面板】由排列对齐、分布对齐、匹配大小、间隔以及相对舞台同几部分组成：

①排列对齐（水平排列和垂直排列）

A.水平排列![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF545.tmp.png)：从左到右分边是水平方向的左对齐、左右居中对齐、右对齐。

B.垂直排列![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF556.tmp.png)：从左到右分边是垂直方向的上对齐、上下居中对齐、下对齐。

②分布对齐（水平分布和垂直分布）：

A.水平分布![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF557.tmp.png)：从左到右分别为垂直方向基于上边缘的分布、基于中心的分布、基于下边缘的分布。

B.垂直分布![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF567.tmp.png)：从左到右分别为水平方向基于左边缘的分布、基于中心的分布、基于右边缘的分布。

③匹配大小![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF568.tmp.png)：将一组对象的宽度、高度或两者调整为对象的最大尺寸。从左到右分别为水平对齐、垂直对齐、水平垂直对齐。

④间隔![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF579.tmp.png)：将一组对象在水平或垂直方向上按照等间距的方式排列。从左到右分别为水平间距的调整、垂直间距的调整。

⑤相对舞台![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF57A.tmp.png)：在默认状态时上述按钮的操作是对于对象本身的，单击此按钮后，则所做的操作是相对于舞台的。

pp��r�\]逐帧动画是一种常见的动画形式\(Frame By Frame\)，其原理是在"连续的关键帧"中分解动画动作，也就是在时间轴的每帧上逐帧绘制不同的内容，使其连续播放而成动画。逐帧动画具有非常大的灵活性，几乎可以表现任何想表现的内容。它类似于电影的播放模式，很适合表演细腻的动画，例如人物走路、说话等。

**学习目的**

本节你将学习掌握以下内容：

逐帧动画的制作方法

插入帧与删除帧

【绘图纸外观】按钮![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF385.tmp.png)的使用方法

【对齐面板】的使用方法



**1.相关概念**

\(1\).空帧

如图4-4-1，空帧在时间轴上就是一个个方格，表示图层中动画的结束。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF396.tmp.jpg)

**图4-4-1 空帧**

\(2\).关键帧

关键帧是制作课件时非常重要的帧，是用来定义动画变化、状态更改的帧。Flash会根据用户正确定义的关键帧，自动完成两个关键帧之间的一些指定的过渡效果。所以只有正确定义了关键帧，才能实现动画制作中的一些由电脑自动完成的过程。如图4-4-2都是关键帧。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF397.tmp.jpg)

**图4-4-2 关键帧**

\(3\).普通帧

普通帧也称为静态帧，用于延长前面一帧的状态，在关键帧后面的普通帧为灰色，在空白关键帧后的普通帧为白色，如图4-4-3。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF3A8.tmp.jpg)

**图4-4-3 普通帧**

\(4\).帧的速度

帧的速度是指动画播放的速度，帧速的单位是FPS（帧/秒），即每秒钟播放的帧数。帧速决定了动画播放的连贯性，帧速太慢，就会明显感觉动画播放的停顿；帧数太快，就会忽略动画的部分细节。



本案例是幼儿园上英语how is the weather的演示课件，它通过逐帧动画演示了几种天气的特点，充分显示了使用flash动画模拟课件再现生活场景的无穷魅力。



**2.制作逐帧动画**



1）文字逐帧动画

逐帧动画适合制作相邻关键帧中对象变化不大的动画。利用flash中的逐帧动画，可以让文字逐个以打字的形式显示出来，此类动画可用于增强课件中文字显示的动感效果。

\(1\)**.**【新建flash文件】打开flash软件，新建一个flash文件、按图 所示操作，设置舞台尺寸为 550×400像素，背景色为白色，其他参数保持默认值。

\(2\).【添加背景图片】新建图层，双击图层名称，将其图层名称修改为【背景图片】，执行【文件】\|【导入到库】，将图片放置在舞台合适位置，如图4-4-4和4-4-5。将该图层的帧延续到第100帧（F5）。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF3B8.tmp.jpg)

**图4-4-4新建图层图4-4-5修改名称**

\(3\).【新建图层【学前英语】 】新建图层，双击图层名称，将其图层名称修改为【学前英语】。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF3B9.tmp.jpg)



\(4\).【输入标题】打开半成品课件“How is the weather”。按图4.4-2-3所示操作，在【学前英语】图层的第25帧添加关键帧（F6）输入文字【学前英语】，并设置字体格式，如图4-4-6和4-4-7。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF3CA.tmp.jpg)

**图4-4-6输入文字**

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF3CB.tmp.jpg)

**图4-4-7颜色面板**

\(5\).【输入How is the weather】新建图层，改名为【How is the weather】，在该图层中我们将实现动态文字的效果，即内容How is the weather按单词顺序依次出现。

\(6\).【延续帧】将所有图层的帧利用F5设置帧延续的第100帧，在图层【How is the weather】的第35帧设置关键帧，如图4-4-8。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF3DB.tmp.jpg)

**图4-4-8延续帧**

\(7\).【制作动态文字效果】

①【添加文本框**】**按图所示操作，在“How is the weather ”图层的第35帧上绘制一个文本框，如图4-4-9所示。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF3EC.tmp.jpg)

**图4-4-9添加文本框**

② 【输入第一个单词】  按图4-4-10,4-4-11,4-4-12所示操作，在文本框内输入第一个单词“How”,修改字体属性，在对齐面板中选择水平中齐。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF3ED.tmp.jpg)

**图4-4-10修改文字属性**

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF3FE.tmp.jpg)

**图4-4-11 水平中齐**

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF40E.tmp.jpg)

**图4-4-12 输入【How】**

③【输入第二个字**】**在“How is the weather”图层的第40帧添加一个关键帧，并在文本框中输入第二个单词“is”，在对齐面板中选择水平中齐，如图4-4-13。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF40F.tmp.jpg)

**图4-4-13 输入【is】**

④【输入其他单词】  重复步骤6，每添加一个关键帧，在文本框内添加一个单词，用对齐面板将其放在适当位置，最终时间轴和舞台效果如图4-4-14和4-4-15。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF420.tmp.jpg)

**图4-4-14舞台效果**

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF440.tmp.jpg)

**图4-4-15时间轴**

⑤**【**多帧调整**】**单击【时间轴】面板下方的【绘图纸外观】按钮![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF451.tmp.jpg)，将写有单词的几帧内容放置在合适位置，如图4-4-16。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF452.tmp.jpg)

**图4-4-16绘图纸外观下的舞台**

⑥【取消多帧查看】单击【绘图纸外观】按钮![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF462.tmp.png)取消其多帧查看效果。









2）制作图形动画



看了我们的半成品课件，我们还会发现，我们cloudy图形动画没有完成，现在我们就来完成这部分课件。

\(1\).【新建图层】  新建图层【cloudy】，放在raining图层和windy图层之中。

\(2\).【新建元件】执行【插入】\|【新建元件】命令，在弹出的对话框中填写元件名称【cloudy】，类型【影片剪辑】元件,如图4-4-17。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF463.tmp.jpg)

**图4-4-17新建元件**



\(3\).【修改图层名称】  在库中打开【cloudy】元件，将元件中图层一改名为【cloudy】。

\(4\).【进行绘图 】

①【画椭圆】在【cloudy】图层的第一帧设置关键帧，在舞台上用椭圆工具绘制一个没有填充颜色的椭圆，如图4-4-18和4-4-19。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF474.tmp.jpg)![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF475.tmp.jpg)

**图4-4-18椭圆工具图4-4-19画椭圆**

②【椭圆组合】在第二帧设置关键帧，复制之前绘制的椭圆，将两个椭圆接在一起，重复几次，如图4-4-20。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF485.tmp.jpg)

**图4-4-20 椭圆组合**

③【删线】删除内部多余的线条，如图4-4-21。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF496.tmp.jpg)

**图4-4-21 云**

（4）【绘制表情】添加关键帧，用【线条工具】绘制表情，每帧绘制不同的部位，最终绘制的图以及时间轴如图4-4-22,4-4-23和4-4-24所示。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF497.tmp.jpg)![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF4A8.tmp.jpg)

**图4-4-22线条工具属性图4-4-23舞台效果**

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF4B8.tmp.jpg)

**图4-4-24时间轴**



（5）【被遮住的太阳】在【cloudy】元件中新建图层【被遮住的太阳】,将新图层放在【cloudy】图层下方，单击【cloudy】图层在【时间轴】面板小黄锁下方的黑点，对此图层进行加锁，如图4-4-25所示。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF4B9.tmp.jpg)

**图4-4-25锁定**

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF4CA.tmp.jpg)

（6）【画太阳】在【被遮住的太阳】的图层第15帧设置关键帧，在舞台上利用椭圆工具，按住ctrl+shift画太阳，利用线条工具画太阳光芒，如图4-4-26。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF4CB.tmp.jpg)

**图4-4-26 半成品**





（7）【添加颜色】添加颜色根据实际情况利用颜色面板和渐变变形工具为云与太阳逐帧添加颜色，如图4-4-27和4-4-28。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF4DB.tmp.jpg)

**图4-4-27颜色面板**

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF4EC.tmp.jpg)

**图4-4-28 cloudy成品**



3\)制作“音乐”图层



在“音乐”图层添加一些声音效果，让动态文字在出现时配上打字的声音，这样会使课件更生动。

\(1\).【添加图层】  在半成品课件中新建图层，并重新命名为“音乐”

\(2\).【添加声音】执行【文件】\|【导入到库】命令导入所要添加的音乐，单击“音乐”图层的第一帧，按图4-4-29所示操作，给图层添加声音效果。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF4ED.tmp.jpg)

**图4-4-29 导入音乐**

\(3\).【插入帧与删除多余的帧】现在可以按“Ctrl+Enter”测试一下动画效果，如果音乐与动画没有合拍，通过插入帧与删除多余帧来进行调整。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF4FE.tmp.jpg)\(4\).【保存并测试课件】  执行【控制】\|【测试影片】命令（快捷键Ctrl+Enter），观察动画效果，如果满意，执行【文件】\|【保存】命令，保存课件。



3.**功能详解**

在前面的动画中，我们利用实例讲解了【对齐面板】中的上对齐功能，还讲解了【绘画纸】里的【绘图纸外观】按钮![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF50E.tmp.png)的使用方法。下面详细的讲解一下【绘画纸】的功能、【对齐面板】的应用，并给大家归纳总结创建逐帧动画的方法。

\(1\)．【绘画纸】的功能

【绘画纸】是一个帮助定位和编辑动画的辅助功能，这个功能对制作逐帧动画特别有用。通常情况下，Flash在舞台中一次只能显示动画序列的单个帧。使用绘画纸功能后，你就可以在舞台中一次查看两个或多个帧了。

如图4-4-30所示，这是使用【绘画纸】功能后的场景，可以看出，当前帧中内容用全彩色显示，其它帧内容以半透明显示，它使我们看起来好像所有帧内容是画在一张半透明的绘图纸上，这些内容相互层叠在一起。当然，这时你只能编辑当前帧的内容。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF50F.tmp.jpg)

**图4-4-30同时显示多帧内容的变化**

【绘画纸】各个按钮的功能：

①![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF520.tmp.png)【绘图纸外观】按钮：按下此按钮后，在时间帧的上方，出现![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF521.tmp.png)绘图纸外观标记。拉动外观标记的两端，可以扩大或缩小显示范围。

②![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF531.tmp.png)【绘图纸外观轮廓】按钮：按下此按钮后，场景中显示各帧内容的轮廓线，填充色消失，特别适合观察对象轮廓，另外可以节省系统资源，加快显示过程。

③![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF532.tmp.png)【编辑多个帧】按钮：按下后可以显示全部帧内容，并且可以进行“多帧同时编辑”。

④![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF533.tmp.png)【修改绘图纸标记】按钮：按下后，弹出菜单，菜单中有以下选项：

A.【始终显示标记】选项：会在时间轴标题中显示绘图纸外观标记，无论绘图纸外观是否打开。

B.【锚定标记】选项：会将绘图纸外观标记锁定在它们在时间轴标题中的当前位置。通常情况下，绘图纸外观范围是和当前帧的指针以及绘图纸外观标记相关的。通过锚定绘图纸外观标记，可以防止它们随当前帧的指针移动。

C.【标记范围2】选项；会在当前帧的两边显示两个帧。

D.【标记范围5】选项；会在当前帧的两边显示五个帧。

E.【标记所有范围】选项；会在当前帧的两边显示全部帧。

\(2\)．【对齐面板】的应用

使用【对齐面板】，可以对编辑区中多个对像进行排列、分布、匹配大小、调整间隔等操作，使布局整齐美观，如图4-4-31所示。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF544.tmp.jpg)

**图4-4-31对齐面板**

【对齐面板】由排列对齐、分布对齐、匹配大小、间隔以及相对舞台同几部分组成：

①排列对齐（水平排列和垂直排列）

A.水平排列![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF545.tmp.png)：从左到右分边是水平方向的左对齐、左右居中对齐、右对齐。

B.垂直排列![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF556.tmp.png)：从左到右分边是垂直方向的上对齐、上下居中对齐、下对齐。

②分布对齐（水平分布和垂直分布）：

A.水平分布![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF557.tmp.png)：从左到右分别为垂直方向基于上边缘的分布、基于中心的分布、基于下边缘的分布。

B.垂直分布![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF567.tmp.png)：从左到右分别为水平方向基于左边缘的分布、基于中心的分布、基于右边缘的分布。

③匹配大小![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF568.tmp.png)：将一组对象的宽度、高度或两者调整为对象的最大尺寸。从左到右分别为水平对齐、垂直对齐、水平垂直对齐。

④间隔![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF579.tmp.png)：将一组对象在水平或垂直方向上按照等间距的方式排列。从左到右分别为水平间距的调整、垂直间距的调整。

⑤相对舞台![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF57A.tmp.png)：在默认状态时上述按钮的操作是对于对象本身的，单击此按钮后，则所做的操作是相对于舞台的。

pp��r�\]插入帧与删除帧

【绘图纸外观】按钮![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF385.tmp.png)的使用方法

【对齐面板】的使用方法



**1.相关概念**

\(1\).空帧

如图4-4-1，空帧在时间轴上就是一个个方格，表示图层中动画的结束。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF396.tmp.jpg)

**图4-4-1 空帧**

\(2\).关键帧

关键帧是制作课件时非常重要的帧，是用来定义动画变化、状态更改的帧。Flash会根据用户正确定义的关键帧，自动完成两个关键帧之间的一些指定的过渡效果。所以只有正确定义了关键帧，才能实现动画制作中的一些由电脑自动完成的过程。如图4-4-2都是关键帧。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF397.tmp.jpg)

**图4-4-2 关键帧**

\(3\).普通帧

普通帧也称为静态帧，用于延长前面一帧的状态，在关键帧后面的普通帧为灰色，在空白关键帧后的普通帧为白色，如图4-4-3。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF3A8.tmp.jpg)

**图4-4-3 普通帧**

\(4\).帧的速度

帧的速度是指动画播放的速度，帧速的单位是FPS（帧/秒），即每秒钟播放的帧数。帧速决定了动画播放的连贯性，帧速太慢，就会明显感觉动画播放的停顿；帧数太快，就会忽略动画的部分细节。



本案例是幼儿园上英语how is the weather的演示课件，它通过逐帧动画演示了几种天气的特点，充分显示了使用flash动画模拟课件再现生活场景的无穷魅力。



**2.制作逐帧动画**



1）文字逐帧动画

逐帧动画适合制作相邻关键帧中对象变化不大的动画。利用flash中的逐帧动画，可以让文字逐个以打字的形式显示出来，此类动画可用于增强课件中文字显示的动感效果。

\(1\)**.**【新建flash文件】打开flash软件，新建一个flash文件、按图 所示操作，设置舞台尺寸为 550×400像素，背景色为白色，其他参数保持默认值。

\(2\).【添加背景图片】新建图层，双击图层名称，将其图层名称修改为【背景图片】，执行【文件】\|【导入到库】，将图片放置在舞台合适位置，如图4-4-4和4-4-5。将该图层的帧延续到第100帧（F5）。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF3B8.tmp.jpg)

**图4-4-4新建图层图4-4-5修改名称**

\(3\).【新建图层【学前英语】 】新建图层，双击图层名称，将其图层名称修改为【学前英语】。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF3B9.tmp.jpg)



\(4\).【输入标题】打开半成品课件“How is the weather”。按图4.4-2-3所示操作，在【学前英语】图层的第25帧添加关键帧（F6）输入文字【学前英语】，并设置字体格式，如图4-4-6和4-4-7。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF3CA.tmp.jpg)

**图4-4-6输入文字**

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF3CB.tmp.jpg)

**图4-4-7颜色面板**

\(5\).【输入How is the weather】新建图层，改名为【How is the weather】，在该图层中我们将实现动态文字的效果，即内容How is the weather按单词顺序依次出现。

\(6\).【延续帧】将所有图层的帧利用F5设置帧延续的第100帧，在图层【How is the weather】的第35帧设置关键帧，如图4-4-8。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF3DB.tmp.jpg)

**图4-4-8延续帧**

\(7\).【制作动态文字效果】

①【添加文本框**】**按图所示操作，在“How is the weather ”图层的第35帧上绘制一个文本框，如图4-4-9所示。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF3EC.tmp.jpg)

**图4-4-9添加文本框**

② 【输入第一个单词】  按图4-4-10,4-4-11,4-4-12所示操作，在文本框内输入第一个单词“How”,修改字体属性，在对齐面板中选择水平中齐。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF3ED.tmp.jpg)

**图4-4-10修改文字属性**

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF3FE.tmp.jpg)

**图4-4-11 水平中齐**

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF40E.tmp.jpg)

**图4-4-12 输入【How】**

③【输入第二个字**】**在“How is the weather”图层的第40帧添加一个关键帧，并在文本框中输入第二个单词“is”，在对齐面板中选择水平中齐，如图4-4-13。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF40F.tmp.jpg)

**图4-4-13 输入【is】**

④【输入其他单词】  重复步骤6，每添加一个关键帧，在文本框内添加一个单词，用对齐面板将其放在适当位置，最终时间轴和舞台效果如图4-4-14和4-4-15。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF420.tmp.jpg)

**图4-4-14舞台效果**

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF440.tmp.jpg)

**图4-4-15时间轴**

⑤**【**多帧调整**】**单击【时间轴】面板下方的【绘图纸外观】按钮![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF451.tmp.jpg)，将写有单词的几帧内容放置在合适位置，如图4-4-16。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF452.tmp.jpg)

**图4-4-16绘图纸外观下的舞台**

⑥【取消多帧查看】单击【绘图纸外观】按钮![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF462.tmp.png)取消其多帧查看效果。









2）制作图形动画



看了我们的半成品课件，我们还会发现，我们cloudy图形动画没有完成，现在我们就来完成这部分课件。

\(1\).【新建图层】  新建图层【cloudy】，放在raining图层和windy图层之中。

\(2\).【新建元件】执行【插入】\|【新建元件】命令，在弹出的对话框中填写元件名称【cloudy】，类型【影片剪辑】元件,如图4-4-17。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF463.tmp.jpg)

**图4-4-17新建元件**



\(3\).【修改图层名称】  在库中打开【cloudy】元件，将元件中图层一改名为【cloudy】。

\(4\).【进行绘图 】

①【画椭圆】在【cloudy】图层的第一帧设置关键帧，在舞台上用椭圆工具绘制一个没有填充颜色的椭圆，如图4-4-18和4-4-19。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF474.tmp.jpg)![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF475.tmp.jpg)

**图4-4-18椭圆工具图4-4-19画椭圆**

②【椭圆组合】在第二帧设置关键帧，复制之前绘制的椭圆，将两个椭圆接在一起，重复几次，如图4-4-20。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF485.tmp.jpg)

**图4-4-20 椭圆组合**

③【删线】删除内部多余的线条，如图4-4-21。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF496.tmp.jpg)

**图4-4-21 云**

（4）【绘制表情】添加关键帧，用【线条工具】绘制表情，每帧绘制不同的部位，最终绘制的图以及时间轴如图4-4-22,4-4-23和4-4-24所示。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF497.tmp.jpg)![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF4A8.tmp.jpg)

**图4-4-22线条工具属性图4-4-23舞台效果**

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF4B8.tmp.jpg)

**图4-4-24时间轴**



（5）【被遮住的太阳】在【cloudy】元件中新建图层【被遮住的太阳】,将新图层放在【cloudy】图层下方，单击【cloudy】图层在【时间轴】面板小黄锁下方的黑点，对此图层进行加锁，如图4-4-25所示。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF4B9.tmp.jpg)

**图4-4-25锁定**

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF4CA.tmp.jpg)

（6）【画太阳】在【被遮住的太阳】的图层第15帧设置关键帧，在舞台上利用椭圆工具，按住ctrl+shift画太阳，利用线条工具画太阳光芒，如图4-4-26。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF4CB.tmp.jpg)

**图4-4-26 半成品**





（7）【添加颜色】添加颜色根据实际情况利用颜色面板和渐变变形工具为云与太阳逐帧添加颜色，如图4-4-27和4-4-28。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF4DB.tmp.jpg)

**图4-4-27颜色面板**

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF4EC.tmp.jpg)

**图4-4-28 cloudy成品**



3\)制作“音乐”图层



在“音乐”图层添加一些声音效果，让动态文字在出现时配上打字的声音，这样会使课件更生动。

\(1\).【添加图层】  在半成品课件中新建图层，并重新命名为“音乐”

\(2\).【添加声音】执行【文件】\|【导入到库】命令导入所要添加的音乐，单击“音乐”图层的第一帧，按图4-4-29所示操作，给图层添加声音效果。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF4ED.tmp.jpg)

**图4-4-29 导入音乐**

\(3\).【插入帧与删除多余的帧】现在可以按“Ctrl+Enter”测试一下动画效果，如果音乐与动画没有合拍，通过插入帧与删除多余帧来进行调整。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF4FE.tmp.jpg)\(4\).【保存并测试课件】  执行【控制】\|【测试影片】命令（快捷键Ctrl+Enter），观察动画效果，如果满意，执行【文件】\|【保存】命令，保存课件。



3.**功能详解**

在前面的动画中，我们利用实例讲解了【对齐面板】中的上对齐功能，还讲解了【绘画纸】里的【绘图纸外观】按钮![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF50E.tmp.png)的使用方法。下面详细的讲解一下【绘画纸】的功能、【对齐面板】的应用，并给大家归纳总结创建逐帧动画的方法。

\(1\)．【绘画纸】的功能

【绘画纸】是一个帮助定位和编辑动画的辅助功能，这个功能对制作逐帧动画特别有用。通常情况下，Flash在舞台中一次只能显示动画序列的单个帧。使用绘画纸功能后，你就可以在舞台中一次查看两个或多个帧了。

如图4-4-30所示，这是使用【绘画纸】功能后的场景，可以看出，当前帧中内容用全彩色显示，其它帧内容以半透明显示，它使我们看起来好像所有帧内容是画在一张半透明的绘图纸上，这些内容相互层叠在一起。当然，这时你只能编辑当前帧的内容。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF50F.tmp.jpg)

**图4-4-30同时显示多帧内容的变化**

【绘画纸】各个按钮的功能：

①![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF520.tmp.png)【绘图纸外观】按钮：按下此按钮后，在时间帧的上方，出现![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF521.tmp.png)绘图纸外观标记。拉动外观标记的两端，可以扩大或缩小显示范围。

②![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF531.tmp.png)【绘图纸外观轮廓】按钮：按下此按钮后，场景中显示各帧内容的轮廓线，填充色消失，特别适合观察对象轮廓，另外可以节省系统资源，加快显示过程。

③![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF532.tmp.png)【编辑多个帧】按钮：按下后可以显示全部帧内容，并且可以进行“多帧同时编辑”。

④![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF533.tmp.png)【修改绘图纸标记】按钮：按下后，弹出菜单，菜单中有以下选项：

A.【始终显示标记】选项：会在时间轴标题中显示绘图纸外观标记，无论绘图纸外观是否打开。

B.【锚定标记】选项：会将绘图纸外观标记锁定在它们在时间轴标题中的当前位置。通常情况下，绘图纸外观范围是和当前帧的指针以及绘图纸外观标记相关的。通过锚定绘图纸外观标记，可以防止它们随当前帧的指针移动。

C.【标记范围2】选项；会在当前帧的两边显示两个帧。

D.【标记范围5】选项；会在当前帧的两边显示五个帧。

E.【标记所有范围】选项；会在当前帧的两边显示全部帧。

\(2\)．【对齐面板】的应用

使用【对齐面板】，可以对编辑区中多个对像进行排列、分布、匹配大小、调整间隔等操作，使布局整齐美观，如图4-4-31所示。

![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF544.tmp.jpg)

**图4-4-31对齐面板**

【对齐面板】由排列对齐、分布对齐、匹配大小、间隔以及相对舞台同几部分组成：

①排列对齐（水平排列和垂直排列）

A.水平排列![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF545.tmp.png)：从左到右分边是水平方向的左对齐、左右居中对齐、右对齐。

B.垂直排列![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF556.tmp.png)：从左到右分边是垂直方向的上对齐、上下居中对齐、下对齐。

②分布对齐（水平分布和垂直分布）：

A.水平分布![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF557.tmp.png)：从左到右分别为垂直方向基于上边缘的分布、基于中心的分布、基于下边缘的分布。

B.垂直分布![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF567.tmp.png)：从左到右分别为水平方向基于左边缘的分布、基于中心的分布、基于右边缘的分布。

③匹配大小![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF568.tmp.png)：将一组对象的宽度、高度或两者调整为对象的最大尺寸。从左到右分别为水平对齐、垂直对齐、水平垂直对齐。

④间隔![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF579.tmp.png)：将一组对象在水平或垂直方向上按照等间距的方式排列。从左到右分别为水平间距的调整、垂直间距的调整。

⑤相对舞台![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsF57A.tmp.png)：在默认状态时上述按钮的操作是对于对象本身的，单击此按钮后，则所做的操作是相对于舞台的。

pp��r�\]

