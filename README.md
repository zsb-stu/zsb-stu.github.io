# 二维

### 小汽车

>1、制作小汽车
   1）设计背景图层，包括背景颜色，马路设计
   2）添加按钮图层（窗口->公用库->按钮->bar capped条状按钮），编辑按钮：连续双击两下，编辑后点击左上角场景一退出
   3）制作小汽车图层	：插入->新建元件->类型：影片剪辑->确定进入小汽车编辑环境
   4）在小汽车图层设计小汽车：建立三个图层：车身，前轮，后轮；
        a）车身：画一个就行
        b）轮子：新建元件->类型：图形->画一个轮子
        c）制作后场景一的库中会有小汽车，车轮两个，右键点击小汽车继续编辑添加轮子
        d）制作后，插入关键帧使小汽车移动
        e）右键创建传统补间，回车键移动
        d)让轮转：先点击振，属性面板有个旋转，指定为顺时针
    5）将小汽车拉到背景面板上，测试：控制->测试影片
    6）让小汽车停止：编辑小汽车，在帧上右键->动作->全局函数，时间轴控制，stop函数，双击使用
    7）设置按钮，先给小汽车命名，然后右键按钮start->开始动作->on（press）{this.名字.gotoAndPlay(1);}
        右键按钮pause->停止动作->on(press){this.名字.gotoAndStop(this.名字._currentframe);}
        右键按钮cont->继续动作->on(press){this.名字.gotoAndPlay(this.名字._currentframe);}
        右键按钮serve->倒退动作->on(press){this.名字.prevFrame();}

# 前端

## HTML

###  标签（可以让页面结构更清晰）名：

​          html:html标签：页面中最大的标签，我们称为跟标签

​          head:文档的头部标签；注意：在head标签中必须设置title标签

​          title：文档的标题标签；让页面拥有一个自定义标题

​          body：文档的主体；元素包含文档的所有内容，页面内容基本放在body标签里面

​         标题标签：h1-h6共六个等级

​         段落标签：p

​         换行标签：br 单目标签

​         文本格式化标签，语义：突出文字重要性

​              加粗：strong 或 b 

​              倾斜：em 或 i

​              删除线：del 或 s

​              下划线：ins 或 u   

<div>和<span>标签，没有语义，像一个盒子，用来装内容。<div>一个独占一行，大盒子；<span>一行可以使用多个，小盒子。

​              图像标签：img src="" 单标签。src是img必须属性，指定图像文件的路径和文件名。

​              图像标签属性：src=“图片”，必须属性

​                       alt=“文本”替换文本，当图片显示不出时，用文本代替

​                       title=“文本”提示文本，鼠标放到图片上显示的文本

​                       width=“ 像素”，height=“ 像素”设置图片宽，高；修改其一，另一个会等比例修改

​                        border=“ 像素”，设置图片边框粗细，一般在CSS设置

​            相对路径：相对于html文件的位置；同级： ；下一级：/;上一级：../；

​            绝对路径：在电脑中的位置，也可以是网络上的地址

​           注意：绝对路径是\；相对路径/。

<div> 
    超链接标签：<a href="跳转目标" target=“目标窗口的弹出方式”>文本或图像</a>
       属性href，作用：用于指定链接目标的url地址（必须属性），标签应用href属性，其就具备超链接功能
       属性target，作用：用于指定链接页面的打开方式，其中_self为默认值（在原有网页上替换），_blank为在新窗口打开（新建窗口打开，保留原有网页）
       外部链接：如：<a href="http://www.baidu.com">百度</a>
       内部链接：如：<a href="本地html文件"></a>
       空连接：<a href="#">空链接，没有地址</a>
       下载链接：如果href里是一个文件或压缩包，会进行下载<a href=“.exe/.zip等文件名”>下载文件</a>
       网页元素链接：在网页中各种网页元素，如文本，图片，视频等都可以添加超链接
                               <a href="http://www.baidu.com"><img src="图片"/></a>
       锚点链接：点击后，快速定位到页面的某个位置 
	                  1）在链接文本的href属性中，设置属性值为“#名字”，如<a herf="#one">第一</a>
	                  2)  在目标文本中设置id属性，并且id=“刚才的名字”，如<h3 id="one">第一简介</h3>
	注释标签：<!--注释-->或Ctrl+/
	特殊字符：用法：符号；

​    

## 

## CSS



## JavaScript





# markdown-note

### 基础篇











