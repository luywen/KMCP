@font-face{

font-family:"Times New Roman";

}

@font-face{

font-family:"宋体";

}

@font-face{

font-family:"等线";

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

p.15{

mso-style-name:"List Paragraph";

margin:0pt;

margin-bottom:.0001pt;

text-indent:21.0000pt;

mso-char-indent-count:2.0000;

mso-pagination:none;

text-align:justify;

text-justify:inter-ideograph;

font-family:等线;

mso-bidi-font-family:'Times New Roman';

font-size:10.5000pt;

mso-font-kerning:1.0000pt;

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

```
mso-page-border-surround-footer:no;}@page Section0{
```

}

div.Section0{page:Section0;}

```
                                                                                    **2.2声音素材的获取与处理**

   **2.2.1声音素材简介**

   在多媒体课件中，语言解说和背景音乐是课件的重要组成部分。按照声音的内容不同，可以将多媒体课件中的声音划分为解说、效果声与音乐声等类型。

    **1.模数转换**

   声音信号，也称为音频信号，是一种连续的模拟信号，计算机可以录制、存储、播放声音，但需要将声音数字化，即以二进制数字格式来表示声音。声音的数字化是将声波进行周期性的采样并将样本数据以离散数字形式存储来实现的。这样模拟信号就转化为数字信号，这个过程称为模数转换，主要包括采样、量化和编码三个步骤。

   （1）采样

    采样是指将时间上连续的信号每隔一定的时间间隔抽取出一个信号的幅度样本，把连续的模拟量用一个个离散的点表示出来，使其成为时间上离散的信号。每秒钟采样的次数称为采样频率;用f表示，单位是赫兹\(Hz\); 两次采样之间的时间间隔称为采样周期，用T表示，则T=1/f。如图2-2-1是一些常见的采样频率。

                                                                      ![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsB7CC.tmp.jpg)

                                                                            **图2-2-1 常见的采样频率**

  （2）量化

   采样得到的幅度值依然是无穷多个实数值中的一个，因此幅度还是连续的。量化是将采样后信号的幅度值用确定的有限位二进制数表示出来的过程。量化的二进制位数称为量化精度或量化位数。量化精度为16bit时称为高保真录音质量，要获得立体声效果，就需要用32bit来保存两个16bit样本。

                                                       ![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsB7DD.tmp.jpg)

                                                                        **图2-2-2  8位量化和16位量化**

 （3）编码

   编码是按一定格式记录采样和量化后的数字音频数据，最简单的编码方式是脉冲编码调制（Pulse Code Modulation，PCM），它的是音质好，但需要较大的存储空间来保存编码数据，CD音乐就是采用这种编码方式。

    模拟、量化和编码后所形成的二进制序列就是数字音频信号，可以将其以文件的形式保存在计算机的存储设备中，这样的文件通常称之为数字音频文件。

                            ![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsB7ED.tmp.png)

                                                                            **图2-2-3   模数转换的过程**

   **2.音频压缩**

   要保存高品质的音频文件就需要大的存储空间，在编码中采用压缩技术可以减小数字音频信号文件的大小，使其更便于存储、传输。音频压缩方法可以分为无损压缩和有损压编。无损压缩是对未压缩音频进行没有任何信息损失的压缩机制，有损压缩是尽可能多的从原文样中删除人耳所不敏感的、没有多大影响的数据，有目的地制成比原文件小得多但音质却基本一样的压缩文件。

    **3.声音素材的常用文件类型**

   （1）波形声音文件

   波形声音是Windows操作系统下的标准数字音频，它是对实际声音的采样。因此，它可以重现各种类型的声音，包括噪声、乐声，以及立体声、单声等。该文件的扩展名为WAV.波形声音的主要缺点是文件的容量较大。例如，以16位量化级44.1K 采样率进行采样的1分钟单声道声音文件大约可达5MB,因此，它不适合于记录长时间、高质量的声音。

   由于原始声音数据量太大，我们的解决方法之一是利用硬件或软件方法进行压缩，另外一种方法是适当降低音质，例如，对于一般人的声音，使用8位量化级和11.025K采样率就可以比较好地进行还原，这样可以将数据量降为原来的18。

   （2）MIDI 文件

   MIDIMausical Instrument Digial Interface文件即乐器指令数字楼口文件，文件扩展名为MID,MIDI文件中的数据是一系列指令。它将乐器弹奏的每个音符表示为一串数字，用来代表音符的声调、力度、长短等，在发声时，经过声卡上的合成器将这组数字进行合成并通过扬声器输出。

  与波形文件相比，MDI 文件的容量要小得多，因此在多媒体课件中的应用广泛。它的主要缺陷是表达能力有限，无法重现自然声音: 其次是MIDI 文件只能记录有限的几种乐器组合，如许多中国民族乐器的乐声就不能记录。

   （3）MPEG Layer 3 文件

   它是目前最流行的声音文件格式之一，因其压缩率大，在刚上音乐、刚络可视电话等领域应用十分广泛，但音质与CD唱片相比要差一些，该文件的扩展名为MP3。

 （4）CDAudio文件

    即音乐CD唱片所采用的文件格式，其扩展名为CDA。该格式文件所记录的是声音的波形流，音质纯正，缺点是无法编辑且文件长度太长。

    **2.2.2 声音的录制与编辑**

    多媒体计算机的教字音频系统由计算机，声卡，以及外部音频部件如麦克风，音机和耳机等组成。在声卡中，数模转换器把从麦克风和其他音频源来的音频模拟信号转换成数字信号，数模转换器把存储在计算机中的教学信号变回模拟信号，通过放大器放大或直接输出该信号进行声音播放。

   在制作多媒体课件时，通常都是利用上述声卡及专用软件来完成声音的录制和播放。Adobe公司开发的Adobe Audition软件就是其中功能比较强大的一款，下面我们以幼儿园大班（上）音乐教材中的《云彩和风儿》的朗读素材为例，对Adobe Audition软件的操作作简单介绍。

                             ![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsB7EE.tmp.jpg)

                                                                     **图2-2-4   Adobe Audition的工作界面**

   **1.声音的录制**

   制作多媒体课件的过程中，可以通过用麦克风录制声音文件、截取正在运行的程序中的声音等方法来录制声音，井保存为WAV格式文件。

   1\)用麦克风录制声音文件

  （1）准备: 首先将麦克风插入声卡的麦克风\(MIC\)插口，打开Audition软件，

  （2） 录音:单击菜单栏上的【文件】\|【新建】\|【新建音频文件】，

                                                                    ![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsB7FF.tmp.jpg)

                                                                            **图2-2-5  “新建音频文件”面板**

   为该文件命名，选择需要的采样率，一般说来，采样频率越高，采样位数越大，声音质量就越好，但相应的声音文件也越大。在这里，我们选择44100Hz，单击【确定】，单击编辑器的“录音按钮”●，此时即可通过麦克风进行录音，完毕后，单击“停止按钮”■即可结東录音。

                                          ![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsB800.tmp.jpg) 

                                                                                     **图2-2-6  录音按钮**

    2\) 截取正在运行的程序中的声音

  （1）做好录音前的准备工作，打开Audition软件，其方法如前所述，

  （2）打开所要运行的程序\(如课件、游戏软件等\)，并找到想要录制的内容，

                                  ![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsB811.tmp.jpg)

                                                                                  **图2-2-7  “首选项”面板**
```

（3）单击【编辑】\|【首选项】\|【音频硬件】，在默认输入的下拉菜单中选择“立体声混音”，单击【确定】，

（4）其余步骤与用麦克风录制声音文件相同。

```
 **2.声音文件的编辑**

  1\)声音编辑

 （1）删除

  在声音素材的编辑过程中，有时需要删除一些空白或者错误的部分，操作如下:选中需要删除的部分，按下键盘上的Delete键，即可删除。

 （2）粘贴

   如果需要把声音文件一部分粘贴到另一个位置，操作如下：选择想要粘贴的部分，同时按下键盘上的Ctrl+c键，单击想要粘贴的位置，再同时按下键盘上的Ctrl+v键即可。

    2\)声音效果的处理

   （1）降噪

    在录制声音素材时，不可避免的会出现一些噪声，这时，我们可以通过降噪处理处理声音素材，操作如下：

    1将该声音文件的波形放大，直到能够清楚地看到该声音文件的低频噪声的波形选中该波段，

    2选择【效果】\|【降噪/恢复】\|【降噪（处理）】，打开效果-降噪面板，

                                               ![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsB821.tmp.jpg)

                                                                        **图2-2-8  “效果-降噪”面板**

    3单击![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsB822.tmp.jpg)，此时，软件会对噪声样本进行分析，接着，单击![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsB833.tmp.jpg)，此时，整个声音素材文件都被选中，接下来，单击面板上的![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsB843.tmp.jpg)按钮，就可以试听降噪的效果了，

    4如果觉得声音失真，可以通过调节“降噪”和“降噪幅度”来设置，

                      ![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsB844.tmp.jpg)

                                                               **图2-2-9  “降噪”和“降噪幅度”选项**

    5如果觉得效果已经理想，单击“应用”按钮，即可完成降噪处理。

      （2）淡入淡出

        在声音素材的开始和结束部分，我们通常需要进行淡入淡出处理来使声音的产生和消失不那么突兀，具体操作如下：

        1向右拖动编辑面板上左上角的淡入标识，即可对声音素材进行淡入处理，

                                                                             ![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsB855.tmp.jpg)

                                                                                 **图2-2-10  “淡入”标识**

    2向左拖动编辑面板上右上角的淡出标识（与淡入标识相同），即可对声音素材进行淡出处理。

    3\)音频的修复

    在录制声音素材的过程中，可能会混入一些杂音，如电话铃声，上课铃声，此时我们就需要进行声音的修复，具体操作如下：

   （1）单击工具栏的“显示频谱频率显示器”![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsB866.tmp.jpg)，调出该声音素材的频谱图，

                                           ![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsB867.tmp.jpg)

                                                                                    **图2-2-11 频谱图**

   （2）单击工具栏的“框选工具”![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsB877.tmp.jpg)，对电话铃声部分进行框选，接着，按下键盘上的Delete键进行删除，

                                                                      ![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsB888.tmp.jpg)

                                                                         **图2-2-12  用框选工具进行框选**

   （3）对于框选不干净的部分，我们可以使用套索工具，单击工具栏的“套索选择工具”![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsB889.tmp.jpg)，将需要删除的部分选出，通过键盘上的Delete键进行清除。

   4）声音的合成

    在多媒体课件中，我们自行录制的声音素材往往需要配上合适的背景音乐或音效，才能达到良好的教学效果，具体操作如下：

   （1）单击【文件】\|【新建】\|【多轨会话】，新建一个多轨会话文件，命名该文件，单击“确定”按钮，此时会出现新建多轨会话的面板，

                                      ![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsB899.tmp.jpg)

                                                                   **图2-2-13  “新建多轨会话”面板**

    （2）将之前录制的《云朵与风儿》的朗读拖到轨道1上，将背景音乐拖到轨道2上，根据朗读声音素材的长度调整背景音乐的长度，

    （3）上下拖动“音量线条”来调节声音素材的音量，通过“淡入”、“淡出”标识对声音素材进行淡入、淡出处理，直到达到理想的效果，

                            ![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsB89A.tmp.jpg)

                                                                             **图2-2-14  音量标识**

   （4）单击【文件】\|【导出】\|【多轨混音】\|【整个文件】，打开“导出多轨混音”面板，选择需要的“格式”、“位置”，单击“确定”，就可以得到配有背景音乐的朗诵了。

                                                   ![](file:///C:\Users\netedi21\AppData\Local\Temp\ksohtml\wpsB8AB.tmp.jpg)

                                                              **图2-2-15  “导出多轨混音”面板**

   **2.2.3 声音素材的制作要求**

   在多媒体课件中的声音的主要作用是引起注意、舒缓等候、提示反应、表示事件进程、提供情景音效、提供反馈等。在一个课件中不可无声，但也不可滥用声音，要从所呈现的教学内容出发。设计声音时要注意不要使用过多的声音，音量最好能够进行调节，多用间歇性的短音乐，声音要与文本、图像、视频等内容相配合。
```



