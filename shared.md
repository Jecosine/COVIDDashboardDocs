# 学院路小学小太阳编程兴趣班

## Table of Contents

[TOC]

## 学术科研以及软件工程工具推荐

### 学术科研

#### 论文检索

- Google Scholar - [https://scholar.google.com/](https://scholar.google.com/)

  > 综合汇总型, 想要的都有, 用过都说好
  >  某匿名用户评价:
  > - ~~"敏感肌也可以用"~~
  > -  ~~"找不到的肯定是'**你的问题**'"~~ 
  > - ~~"不像百度学术, 我只会心疼xx"~~

- Research Gate - [https://www.researchgate.net/](https://www.researchgate.net/)

  > 综合性的科研论坛+资料库
  >  
  > - 提供论文以及书籍的基本信息和获取途径
  > - 与研究者交流与讨论
  > - 论文推荐系统
  > - 前沿研究进展

- Paper with Code - [https://www.paperswithcode.com/](https://www.paperswithcode.com/)

  > 汇总网站, 把某些领域(*主要是ML方向*)的论文和代码汇总起来

- Scopus

  > 同行评议文献数据库, 国外认可度更高.
  > ~~现在看看也就用下论文的引用关系查询，方便收集论文后面的参考文献~~
  > ~~*"不会吧, 不会真的有在上面发了的大佬吧" --《极度恐慌》*~~

- arXiv.org

  > 非正式的电子印刷文档镜像, 里面的文献有些并未发表
  > Tips: 
  > 个人也可以在上面随便发, 但是不建议, 因为如果写的烂可能会影响你的学术评价, 
  > 而且有些期刊要求文章不能在上面发表过

- Engineer Village

  >  ~~都知道了, 就不说了:)~~

- IEEE

  > ~~都知道了, 就不说了:)~~

- Web of Science

  >  ~~都知道了, 就不说了:)~~

#### 参考资料检索

- Library Genesis - [http://libgen.rs/](http://libgen.rs/)
  > 未印刷的电子版本, 有点像arXiv
  > 检索范围: 书, ~~文章?~~
- ~~Allitebooks~~
- ZLibrary - [https://1lib.us/](https://1lib.us/) [https://z-lib.org/](https://z-lib.org/)
- 鸠摩电子书 - [https://www.jiumodiary.com/](https://www.jiumodiary.com/)

#### 阅读与文献管理工具

- Mendeley - [https://www.mendeley.com/](https://www.mendeley.com/)
  
  > 提供了浏览器插件, 下载文献
  
- Zotero - [https://www.zotero.org/](https://www.zotero.org/)
  
  > **开源**
  
- Citavi - [https://citavi.com/](https://citavi.com/)
  
  > 免费版限制单个文档内100个参考文献
  
- endnote - [https://endnote.com/](https://endnote.com/)
  
  > 老牌, 全面, UI好康, 就是要钱

#### Latex

$\LaTeX$是广为人知的基于$\TeX$文档排版系统, 主要是理工科方向的用的多, 通过代码的方式定制你的各种样式, 控制论文的排版等

**Overleaf**

在线的latex文档编辑与管理平台

- 快速编译
- 众多模板, 大部分大学/期刊/会议的论文标准模板都有在上面.

**TexStudio**

- 官方工具, 功能全面
- ~~界面丑, 10年前的风格~~

**Visual Studio Code**

- 通过插件**Latex Workshop**来实现对Latex编辑的支持
- 提供默认工作流, 也可以自定义(当使用某些宏包的时候也许需要修改编译参数)
- 界面美观好看
- 界面美观好看
- 界面美观好看

**Jetbrains?**

- ~~先把Markdown支持做好再说吧,球球了~~

#### 知识库管理

- Obsidian
- ~~静态博客生成器也不错~~
  
  > 标签化管理
  > 开放的插件社区
  > 双向引用
  > 美观的界面风格, 斯巴拉西

- 语雀等...
  
  > 没用过, 听说不戳

### 软件工程

> *游戏是儿童最正当的行为，玩具是儿童的天使* 
>
> <div style="text-align:right">--鲁迅</div>

#### 字体

<div style="font-family: 'FiraCode NF'; font-size: 2em">FiraCode</div>

开源的免费Monospace字体, 支持连字(Ligature)
link: [https://github.com/tonsky/FiraCode](https://github.com/tonsky/FiraCode)

![image-20210611045355435](img/image-20210611045355435.png)

![image-20210611045444963](img/image-20210611045444963.png)

![image-20210611045720806](img/image-20210611045720806.png)

安装下载之后, 在IDE里面选择字体就行了, **记得打开Ligature选项**

#### Typora主题推荐

Markdown 渲染~~进化~~的本质 -- HTML
Theme 的本质 -- CSS ~~或其变态发育版(如scss, less)~~

例子:
<div style="
            border-radius:1em;
            padding-left: 4em!important;
            color:white;
            line-height: 3em;
            height: 3em;
            background-image:linear-gradient(to right, #dd2244, #9999ee)">
  This background is linear gradient
</div>

```html
<div style="border-radius:1em;
            padding-left: 4em!important;
            color:white;
            line-height: 3em;
            height: 3em;
            background-image:linear-gradient(to right, #dd2244, #9999ee)">
  This background is linear gradient
</div>
```

推荐: 
- **Blubook**
- **Vue**

<u>**根本原因 - 字体**</u>:

- <div style="font-family:'Noto Sans SC'; font-size: 1.2em"> Noto Sans SC 无衬线 </div>
- <div style="font-family:'Noto Serif SC'; font-size: 1.2em"> Noto Serif SC 有衬线 </div>


#### Atom Icon Plugin

![image-20210611051933451](img/image-20210611051933451.png)

#### Git

版本管理系统(Version Control System)

![image-20210611052711810](img/image-20210611052711810.png)

图形化管理:

- GitKraken - 有学生优惠, ~~也可以直接破解~~

![image-20210611052700256](img/image-20210611052700256.png)

- SourceTree - 开源免费 (但是在windows下界面不太好康)

#### 学生福利

- Github
- Jetbrains
- 
