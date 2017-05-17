# HTML

### <元信息meta>

1、设置页面关键字

    <meta name = “keywords” content = “插入关键字”>

2、设置页面说明

    <meta name = “description” content = “设置页面说明”>

3、定义编辑工具

    <meta name = “generator” content = “编辑软件的名称”>

4、设置作者信息

    <mate name = “author” content = “作者的姓名”>

5、设置网页文字及语言

    <meta http-equiv = “content-type” content = “text/html” ;charset = “字符集类型”>

6、设置网页的定时跳转

    <meta http-equiv = “refresh” content = “跳转的时间；URL = 跳转的地址”>

### <主题标记body>

1、背景颜色

<bgcolor = “#FF99FF”>

2、background属性可以设置图片为背景

    <background = “图片地址”>

3、text可以设置文字的颜色

    <text = “#9966CC”>

4、link可以设置链接文字的颜色，alink可以设置正在访问的文字颜色,vlink访问后的字体颜色

     <link = “#993300 alink = “#0066FF”” vlink = “#336600”>

5、边距margin(上边距、左边距)

    <body topmargin = “100” leftmargin = “100”>

### <h标题>

1、align对齐方式

    <h1 align = “left”>左对齐</h1>
    <h1 align = “center”>居中</h1>
    <h1 align = “right”>右对齐</h1>

2、font字体，字号和颜色等属性

    <font face = “字体”>
    <font size = “字号”>
    <font color = “颜色”>
    <p><font face = “宋体” size = “10” color = “#993300”></font></p>

3、b、strong粗体

    <p><b>粗体</b></p>
    <p><strong>粗体</strong></p>

4、斜体i、em、cite

    <p><i>i斜体</i></p>
    <p><em>em斜体</em></p>
    <p><cite>cite斜体</cite></p>

5、上标标记sup标签、下标标记sub
   a<sup>2  = a^2 
   h<sub>2 = h2

6、下划线

    <u>下划线标签</u>

7、换行标签.不换行标签
    
    <br></br> <nobr></nobr>

8、水平线

    <hr width = “500” size = “3”  color = “”#CC6600 noshade(无阴影)>

### <图像image>

    <src = “图像文件的地址”>
    <alt = “提示文字”>
    <width = “宽” height = “高”>
    <border = “边框”>
    <vspace = “垂直边距”>
    <hspace = “水平边距”>
    <align = “排列方式”>
    <dynsrc = “设定avi文件的播放”>
    <loop = “设定avi文件循环播放次数”>
    <loopdelay = “设定avi文件循环播放延迟”>
    <start = “设定avi播放方式”>
    <lowsrc = “设定低分辨率图片”>
    <usemap = “映像地图”>

### <列表>
1、有序列表ol

    <ol  type = “序号类型” start = “2”(可以修改起始数值)>
      <li type = “1”>1、2、3、</li>
      <li type = “a”>小写英文字母a、b、c</li>
      <li type = “A”>大写英文字母A、B、C</li> 
      <li type = “i”>小写罗马数字i、ii、iii</li>
      <li type = “I”>大写罗马数字I、II、III</li>
    </ol>

2、无序列表ul

    <ul type = “符号类型”>
      <li  type = “Disc”>默认值，黑色实心圆点</li>
      <li type = “circle”>空心圆环</li>
      <li type = “square”>正方形</li>
    </ul>

3、定义列表标记dl

    <dl>
        <dt>定义条件</dt>
        <dd>定义描述</dd>
    </dl>

### <表格>

    <table width = “表格的宽” height = “表格的高” border = “表格的边框宽度” bordercolor = “表框颜色” cellspacing = “内框宽度” cellpadding = “文字与边框间距” bgcolor = “背景颜色” background = “背景图像” align = “表格水平对齐”>

    <caption>表格的唯一标题</caption>
    <thead>表首标记</thead>
    <th>表头</th>
    <tr height、bordercolor、bgcolor、background、align、valign = “垂直对齐方式”>表格行的开始和结束</tr>
    <td width、height、bgcolor、>表格格的开始和结束</td>
    <tfoot>表尾</tfoot>
    </table>

### <链接>

1、内部链接：与自身网站页面有关的链接

    <a href = “链接地址” target = “目标窗口的打开方式”>
      <target = “_self”>在当前页面中打开链接
      <target = “_blank”>在一个全新的空白窗口打开链接
      <target = “_top”>在顶层框架中打开链接
      <target = “_parent”>在当前框架的上一层打开链接
    </a>

2、瞄点链接

    <a name = “瞄点的名称”></a>
    <a href = “#名称”>链接同一界面的瞄点</a>

3、外部链接：当前网站之外的资源中

    <a href = “http://….”>外部链接地址</a>
    <a href = “mailto:E-mail”>E-mail输入邮箱地址</a>
    <a href = “ftp://ftp….”>FTP文件传输网站</a>
    <a href = “mp3.rar”>文件下载地址 、</a>

### <添加多媒体>

1、滚动标记marquee标签

    <marquee>这标记之间添加要进行滚动的内容，并可以在标记之间设置文字或者图像的属性</marquee>

2、滚动方向direction和滚动方式behavior

    <marquee direction = “up” behavior =“scroll”>向上、循环滚动，默认效果</marquee>
    <marquee direction = “down” behavior = “slide”>向下、滚动一次就停止</marquee>
    <marquee direction = “left” behavior = “alternate“””>向左、来回交替进行滚动</marquee>
    <marquee direction = “right”>向右</marquee>

3、滚动速度和滚动延迟

    <marquee scrollamount = “int” scrolldelay = “int”>滚动速度、滚动延迟时间<marquee>

4、循环滚动loop

    <marquee loop = “循环滚动次数”></marquee>

5、滚动范围width、height

    <marquee width = “宽” height = “高”></marquee>

6、滚动的背景色

    <marquee bgcolor = “#993300”>十六进制颜色值</marquee>

7、滚动的空白空间hspace、vspace

    <marquee hspace = “水平范围” vspace = “垂直范围”></marquee>

8、插入多媒体Flash、音视频

    <embed src = “多媒体文件地址、音视频文件地址” width = “多媒体的宽度” height = “多媒体的高度”>

9、背景音乐bgsound

    <bgsound  src = “背景音乐的地址” loop = “播放次数”（ture为无限次的播放）>

10、插入Java Applet

    <applet code = “Lake.class” width = “宽度” height = “高度”>
    <param name = “文件夹的名称” value = “图片名称”>
    </applet>

<框架结构>

1、水平分割窗口rows（像素或者百分比）

    <frameset rows = “框架窗口的高度，框架窗口的高度….”>
    <frame src = “top.html” name = “mainFrame” id = “mainFrame” scolling = “No”（控制框架滚动条显示） noresize = “noresize”（窗口尺寸大小不可调）>
    <frame scr = “foot.html” name = “bottomFrame” id = “bottomFrame” >
    …
    </frameset>

2、垂直分割窗口cols（像素或者百分比）

    <frameset cols = “框架窗口的宽度，框架窗口的宽度…” framespacing = “0”(框架的边框宽度) frameborder = “no”（框架的边框） border = “0” bordercolor = “#996633”（框架的边框颜色）>
    <frame src = “left.html”（页面源文件） name = “leftFrame”（页面名称） id = “leftFrame” marginwidth = “水平边距” marginheight = “垂直边距”>
    <frame src = “left1.html”>
    <frame src = “right.html” name = “rightFrame” id = “rightFrame”>
    …
    </frameset>

3、嵌套分割窗口

    <frameset rows = “” cols = “*”>
    <frame>
    <frameset cols = “”>
    <frame>
    <frame>
    ...
    </frameset>
    </frameset>

4、不支持框架<noframes>

5、浮动框架iframe

    <iframe src = “浮动框架的源文件” width = “宽” height = “高” align = “对齐方式” scrolling = “滚动条属性”（auto：左对齐；yes：总是显示滚动条；no：不显示滚动条）><iframe>

### <表单标记form>

1、提交表单action

       <form action = “表单的处理程序” name = “表单名称”>       </form>

2、表单传送方法method

       <form method = “get”(表单呗传送到action属性指定的URL，然后这新URL被送到处理程序上)>       </form>
       <form method = “post”(表单数据包含在表单主体中，然后被送到处理程序上)>       </form>

3、编码方式enctype

       <form enctype = “application/x-www-form-urlencoded”(默认编码形式)>       </form>
       <form enctype = “multipart/form-data”(上传文件的表单)>

4、目标显示方式target

         <form target = “_self”>在当前页面中打开链接
         <form target = “_blank”>在一个全新的空白窗口打开链接
         <form target = “_top”>在顶层框架中打开链接
         <form target = “_parent”>在当前框架的上一层打开链接

5、插入表单对象

*文字字段text
      
     <input name = “控件名称” type = “text” value = “文字字段的默认取值” size = “控件的长度” ，maxlength = “最长字符数”>

*密码域password
    
     <input name = “控件名称” type = “password” value = “文字字段的默认取值” size = “控件的长度” ，maxlength = “最长字符数”>

*单选按钮

    <input name = “按钮名称” type = “radio”  value = “单选按钮的值” checked/>

*复选框checkbox
       
    <input name = “复选框名称” type = “checkbox” value = “复选框的值” checked/>

*普通按钮button
      
     <input name = “按钮名称” type = “submit” value = “按钮的取值” onclick = “处理程序”/>

*重置按钮reset
      
     <input name = “按钮名称” type = “reset” value = “按钮的取值” />

*图像域image
      
     <input name = “图像的名称” type = “image” src = “图像的地址”>

*隐藏域hidden
     
      <input name = “隐藏域的名称” type = “hidden” value = “隐藏域的取值” />

*文件域file
    
     <input name = “文件域的名称” type = “file” size = “控件的长度” maxlength = “最长字符数”>

6、菜单和列表

*下拉菜单
     
    <select name = “下拉菜单名称”>
       <option value = “选项值” selected(首选值)>选项显示内容
       …..
    </select>

*列表项

       <select name = “列表项的名称” size = “显示的列表项数” nultiple>
       <option value = “选项值” selected>选项显示内容
       ……
       </select>

7、文本域标记textarea

     <textarea name = “文本域名称” cols = “列数” rows = “行数”>       </textarea>

8、id标记

      <id = 元素的标识名>

/***
   全部HTML小的操作及练习
**/











