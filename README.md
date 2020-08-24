<div>
<img src="https://shekelash.github.io/jekyll-theme-archive/img/Screenshot01.png" width="45%">
<img src="https://shekelash.github.io/jekyll-theme-archive/img/Screenshot02.png" width="45%">
</div>

# archive
适合发布小说的Jekyll主题。A Jekyll theme for fiction.
<br>

<a target="_blank" href="https://shekelash.github.io/">DEMO</a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a target="_blank" href="https://github.com/shekelash/jekyll-theme-archive/">Fork/Download</a> 
<br>
DOME展示为私人博客，根据个人需要进行了细节修改，与实际效果略有不同。  

### 特点

- 布局参考了AO3，更适合发布小说
- 极简的版面与CSS，打开页面（相对）飞快。
- 分类与标签页
- 搜索插件

### 已知但难以修复的问题

- 横屏状态下，内文较多时页面会被撑大几个像素。
- 初次搜索有点慢，如果显示无搜索结果就随便再多打一个字进去，随后删除该字。多试几次。

### 鸣谢

  静态网页生成器：<a target="_blank" href="https://github.com/jekyll/jekyll">jekyll</a>  
  搜索脚本：<a target="_blank" href="https://github.com/christian-fei/Simple-Jekyll-Search">Simple-Jekyll-Search</a>，
  图标：<a target="_blank" href="https://fontawesome.com/">font Awesome</a>，
  按钮特效：<a target="_blank" href="https://ianlunn.github.io/Hover/">Hover.css</a>  
  主题缝合自：<a target="_blank" href="https://github.com/ronv/sidey">sidey</a>，
  <a target="_blank" href="https://github.com/fongandrew/hydeout">hydeout</a>，
  <a target="_blank" href="https://github.com/PandaSekh/Jekyll-YAMT">Jekyll-YAMT</a>，
  <a target="_blank" href="https://github.com/xz-777/H-Plus">H-Plus</a>

# 使用方法

### 初步安装
1. 进入<a target="_blank" href="https://github.com/shekelash/jekyll-theme-archive/">本主题项目页</a>，点击右上角**Fork**按钮。等待该项目复制到你的Github。
2. Fork按钮下一行，Code开头的那一行按钮，点击最后那个**Setting**按钮，将**Repository name(仓库名称)** 修改为：[你的用户名].github.io
3. 打开https://[你的用户名].github.io 网页，等待3-5分钟后刷新出现页面。你的博客就建好了。

### 自定义修改
1. **_config.yml** 用于修改博客属性，按给出的提示改
2. **/date/navigation.yml** 侧边栏，按自己的需要改。不需要的内容可以删除
3. **/date/social.yml** 侧边栏最下一行图标，按自己的需要改。不需要的内容可以删除，需要的内容相应修改成自己的网址
4. **_pages/about.md** About页，可改成自己的介绍。按给出的提示改

### 发布
1. 文章保存至 **_posts**文件夹即可发布。
2. 文章需按照一定的规则命名，且文章头部需要按照一定规则填写，具体请参考 **_posts/README.md**文件。
3. 加粗、加黑等格式可使用MarkDown语法。
4. 换行：回车后需要加两个空格（GitHub上特有的问题）
5. 空2行以上：需使用\<br>代码空行（GitHub上特有的问题）

### 注意
1. 每次修改/发布后需等待3-5分钟，才能刷新出新内容。
