&lt;!--

/\* Font Definitions \*/

@font-face

```
{font-family:宋体;

panose-1:2 1 6 0 3 1 1 1 1 1;

mso-font-alt:SimSun;

mso-font-charset:134;

mso-generic-font-family:auto;

mso-font-pitch:variable;

mso-font-signature:3 680460288 22 0 262145 0;}
```

@font-face

```
{font-family:"Cambria Math";

panose-1:0 0 0 0 0 0 0 0 0 0;

mso-font-charset:0;

mso-generic-font-family:roman;

mso-font-pitch:variable;

mso-font-signature:-536870145 1107305727 0 0 415 0;}
```

@font-face

```
{font-family:等线;

panose-1:2 1 6 0 3 1 1 1 1 1;

mso-font-alt:DengXian;

mso-font-charset:134;

mso-generic-font-family:auto;

mso-font-pitch:variable;

mso-font-signature:-1610612033 953122042 22 0 262159 0;}
```

@font-face

```
{font-family:"\@宋体";

panose-1:2 1 6 0 3 1 1 1 1 1;

mso-font-charset:134;

mso-generic-font-family:auto;

mso-font-pitch:variable;

mso-font-signature:3 680460288 22 0 262145 0;}
```

@font-face

```
{font-family:"\@等线";

panose-1:2 1 6 0 3 1 1 1 1 1;

mso-font-charset:134;

mso-generic-font-family:auto;

mso-font-pitch:variable;

mso-font-signature:-1610612033 953122042 22 0 262159 0;}
```

/\* Style Definitions \*/

p.MsoNormal, li.MsoNormal, div.MsoNormal

```
{mso-style-unhide:no;

mso-style-qformat:yes;

mso-style-parent:"";

margin:0cm;

margin-bottom:.0001pt;

text-align:justify;

text-justify:inter-ideograph;

mso-pagination:none;

font-size:10.5pt;

mso-bidi-font-size:11.0pt;

font-family:等线;

mso-bidi-font-family:"Times New Roman";

mso-font-kerning:1.0pt;}
```

.MsoChpDefault

```
{mso-style-type:export-only;

mso-default-props:yes;

font-size:10.0pt;

mso-ansi-font-size:10.0pt;

mso-bidi-font-size:10.0pt;

font-family:等线;

mso-ascii-font-family:等线;

mso-fareast-font-family:等线;

mso-hansi-font-family:等线;

mso-font-kerning:0pt;}
```

/\* Page Definitions \*/

@page

```
{mso-page-border-surround-header:no;

mso-page-border-surround-footer:no;}
```

@page WordSection1

```
{size:595.3pt 841.9pt;

margin:72.0pt 90.0pt 72.0pt 90.0pt;

mso-header-margin:42.55pt;

mso-footer-margin:49.6pt;

mso-paper-source:0;

layout-grid:15.6pt;}
```

div.WordSection1

```
{page:WordSection1;}
```

--&gt;

**4.8利用引导线动画制作课件**

**1.认识引导动画**

运动引导层动画是指对象沿着某种特定的轨迹进行运动的动画，特定的轨迹也被称为固定路径或引导线。作为动画的一种特殊类型，运动引导层的制作需要至少使用两个图层，一个是用于绘制特定路径的运动引导层，另一个是用于存放运动对象的图层（如图4-8-1），在最终生成的动画中，运动引导层的引导线不会显现出来。

![](/assets/4-8-1.png)

**图4-8-1 单个被引导层（对象图层）**

运动引导层就是绘制对象运动路径的图层，通过此图层中的运动路径，可以引导被引导层中的对象沿着绘制的路径运动。在时间轴面板中，一个运动引导层下可以有多个图层（如图4-8-2），也就是多个对象可以沿同一条路径同时运动，此时运动引导层下方的各个图层也就成为被引导图层。

![](/assets/4-8-2.png)

**图4-8-2 多个被引导层（对象图层）**

**2.创建引导线动画**

使用鼠标单击被引导层创建【传统引导层】是一种比较快捷的方法，具体步骤如下：

\(1\)首先，在【时间轴】面板中选择需要创建动作引导层的图层。

\(2\)鼠标右键单击该图层，从弹出的【菜单】中选择【添加传统引导层】命令，即可在所选图层上面创建一个运动引导层（此时，创建的引导层前面会出现一个图标![](file:///C:/Users/netedi21/AppData/Local/Temp/msohtmlclip1/01/clip_image006.png) ），并且将原来所选图层设为引导层，如图4-8-3所示。

![](/assets/4-8-3.png)

**图4-8-3 创建传统引导层**

\(3\)在引导层中绘制一条直线（或者曲线），来指定运动的路径，如图图4-8-4所示。

![](/assets/4-8-4.png)

**图4-8-4 在引导层绘制直线**

**注意：一个引导层可以引导多个被引导层。**

\(4\)从【库】中把准备好的素材拖入到被引导层，调整素材大小直至合适。

\(5\)在被引导层制作一个【传统补间动画】，如图4-8-5所示。

![](/assets/4-8-5.png)

**图4-8-5 导入素材**

\(6\)鼠标左键单击传统补间动画补间线，在【属性】面板里勾选【补间】栏里面的【调整到路径】，如图4-8-6所示。

![](/assets/4-8-6.png)

**图4-8-6 调整到路径**

\(7\)在引导层的时间轴上与被引导层末尾帧一样的位置，按【F5】延长引导层的时间帧数到与被引导层一样，如图4-8-7所示。

![](/assets/4-8-7.png)

**图4-8-7 延长引导层帧数**

\(8\)调整补间动画的第一帧中素材的位置，使素材的中心点在引导线上你需要的位置（这里以端点为例），如图4-8-8所示。

![](/assets/4-8-8.png)

**图4-8-8 调整补间动画第一帧位置**

\(9\)调整最后一帧素材的位置，同样使素材的中心点在引到线上你需要的位置（这里以端点为例），如图4-8-9所示。

![](file:///C:/Users/netedi21/AppData/Local/Temp/msohtmlclip1/01/clip_image018.png)![](/assets/4-8-9.png)

**图4-8-9 调整素材最后一帧位置**

\(10\)同时按住【Ctrl+enter】键播放，效果如图4-8-10所示（双击图片播放）。

![](/assets/4-8-10.png)

**图4-8-10 效果预览**

\(11\)那曲线的引导线该怎样做呢？首先，跟方法（1）～（7）步骤一样，只是将（3）中的直线改为曲线（这里以圆为例子），如图4-8-11所示。

![](/assets/4-8-11.png)

**图4-8-11 画圆形引导线**

\(12\)跟（8）步骤一样，调整补间动画的第一帧中素材的位置，使素材的中心点在引导线上你所想要的位置，如图4-8-12所示。

![](/assets/4-8-12.png)

**图4-8-12 调整素材第一帧位置**

\(13\)注意：曲线会改变方向，如果跟直线一样的做法，效果会很呆、不符合事实。因此，我们在圆形的上下左右分别调整位置和方向（或者更精细）（注意中心点要在引到线上），如图4-8-13所示。

![](/assets/4-8-13.png)![](/assets/4-8-13..png)![](/assets/4-8-13...png)

**图4-8-13调整素材在上下左位置时的位置**

\(14\)效果预览，如图4-8-14所示（双击图片播放）。

![](/assets/4-8-14.png)

**图4-8-14效果预览**

\(15\)调整细节，效果满意后【保存文件】。



