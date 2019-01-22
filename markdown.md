1. <a href="#tag-是什么?">是什么?</a> 
1. <a href="#tag-能干什么">能干什么</a>
1. <a href="#tag-行业应用">行业应用</a>
1. <a href="#tag-政策">政策</a>
1. <a href="#tag-巨头战略">巨头战略</a>
1. <a href="#tag-创企">创企</a>
1. <a href="#tag-开放平台">开放平台</a>
1. <a href="#tag-开源">开源</a>
1. <a href="#tag-学习资源">学习资源</a>
1. <a href="#tag-Tools">Tools</a>
1. <a href="#tag-实际操作">实际操作</a>
1. <a href="#tag-业界动态">业界动态</a>

# <a id="tag-是什么?" href="#tag-是什么?">是什么?</a>
# <a id="tag-能干什么" href="#tag-能干什么">能干什么</a>
# <a id="tag-行业应用" href="#tag-行业应用">行业应用</a>
# <a id="tag-政策" href="#tag-政策">政策</a>
# <a id="tag-巨头战略" href="#tag-巨头战略">巨头战略</a>
# <a id="tag-创企" href="#tag-创企">创企</a>
# <a id="tag-开放平台" href="#tag-开放平台">开放平台</a>
# <a id="tag-开源" href="#tag-开源">开源</a>
# <a id="tag-学习资源" href="#tag-学习资源">学习资源</a>
# <a id="tag-Tools" href="#tag-Tools">Tools</a>
# <a id="tag-实际操作" href="#tag-实际操作">实际操作</a>
# <a id="tag-业界动态" href="#tag-业界动态">业界动态</a>


# windows markdown 
https://atom.io/

# 表格模板 & 表中超链接
<table>
    <tr>
        <th></th>
        <th>何时发布</th> <!注释>
        <th>主要功能</th> 
        <th>背后语音</th>
        <th>服务扩展</th>
        <th>生态</th>
        <th>市占率</th>
        <th>能力级别</th>
    </tr>
    <tr>
        <th><a href = "https://baike.baidu.com/item/%E5%B0%8F%E7%88%B1%E5%90%8C%E5%AD%A6/22047751?fr=aladdin">小爱同学</a> </th>
        <th></th> <!何时发布>
        <th></th> <!主要功能>
        <th></th> <!背后语音>
        <th></th> <!服务扩展>
        <th></th> <!生态>
        <th></th> <!市占率>
        <th></th> <!能力级别>
    </tr>    
    <tr>
        <th>天猫精灵</th>
        <th></th> <!何时发布>
        <th></th> <!主要功能>
        <th></th> <!背后语音>
        <th></th> <!服务扩展>
        <th></th> <!生态>
        <th></th> <!市占率>
        <th></th> <!能力级别>
    </tr>  
</table>

# 表格合并

<table> 
    <tr> #<tr></tr>的个数为：行数 <td rowspan="7"> 合并多行成一列：<br/> #<td></td>的个数为：列数 使用rowspan="n" <br/> 跨 n 行合并<br/> </td> <td>文件标识：</td> <td>内容</td> </tr> <tr> <td>第一行：</td> <td>该写什么呢？</td> </tr> <tr> <td>第二行：</td> <td>随便写吧！</td> </tr> <tr> <td>第三行：</td> <td>OK了！</td> </tr> 
</table>


# 插入图片
![插入图片]()<br>

# 超链接模板
[superlink]()<br>

table {
    width: 100%; /*表格宽度*/
    max-width: 65em; /*表格最大宽度，避免表格过宽*/
    border: 1px solid #dedede; /*表格外边框设置*/
    margin: 15px auto; /*外边距*/
    border-collapse: collapse; /*使用单一线条的边框*/
    empty-cells: show; /*单元格无内容依旧绘制边框*/
}
table th,
table td {
  height: 35px; /*统一每一行的默认高度*/
  border: 1px solid #dedede; /*内部边框样式*/
  padding: 0 10px; /*内边距*/
}
