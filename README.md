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

<h1 align = “left”>左对齐</h1><h1 align = “center”>居中</h1><h1 align = “right”>右对齐</h1>

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
  a<sup>2  = a^2  h<sub>2 = h2

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











