# Phisics-Homework  
>用于储存大物作业  
>本人偷懒用markdown，LaTex佬别骂我QAQ  
>也许以后会更新一点学大物的经验什么的，但这取决于我大物考得怎样。

->[目录](./目录.md)  

## 前言

建立本仓库的原意是作为之前上传的习题解答的补充。~~储存作业只是顺便~~  
相当于习题解答勘误加详解吧。  
~~文件夹中的.md文件用于在github上直接查看，下载查看可选pdf文件。~~  
直接查看和下载查看都请查看pdf文件吧，github并不支持KaTex渲染，大意了。可以看看想看看如何手敲作业的可以瞧瞧.md文件。    
**:warning:请勿抄袭！**

## 作业  
- 作业范围：每一届可能会有不同，但应该差别不大。
- 本人作业质量：应该还行，两年多的物理竞赛应该不是白学的，想~~抄袭~~借鉴的同学大可放心。本人有强迫症，所以过程相对详细。
- 关于作业：写作业是学习大物不可少的过程，希望大家只是用来参考。你如果想抄袭的话没人拦得住你。
- 关于作业形式：老师当然是要求独立完成啦，一般还是手写吧。听说有部分老师要求使用LaTex完成物理作业，但不是计科的。手写建议使用平板或者数位板，便于修改，最后打印提交。如果有像我一样想要手敲的人，推荐使用markdown，不为什么，轻量且无需配置，markdown赛高！

## 推荐参考书目  
- 个人觉得计科的大物课本讲得较浅，想要深入学习的可以使用那几本经典物理竞赛教程。
- 高数I。没错，就是高数I。会大量使用到微积分的思想，还有解简单的微分方程。

## 关于~~作死~~手敲作业的建议  
对想要和我一样~~作死~~手敲作业，且和我一样偷懒使用markdown的同学的几点建议：  

1. 熟悉LaTex的公式语法，因为markdown的公式继承自Tex，且使用KaTex(或者其他类似东西)进行渲染。
2. 记住常用符号的转义。如`\int`$\to\int$，`\dot{x}`$\to\dot{x}$。
3. markdown唯一的缺点可能就是不能像LaTex一样自动为公式进行编号，但可使用`\tag{1}`或`\tag*{1}`进行手动编号。
4. 作图可在纸上作图并拍照或用软件绘图。推荐使用HTML标签插入图片，因为markdown自带的插入方法无法调节图片大小。  
例：`<img src=1_12.png width="30%">`其中`1_12.png`是图片的绝对或相对路径，`30%`是图片比例。
5. markdown编辑器无推荐，只要支持数学编辑，有实时预览或者预览加同步滚动就行。同时由于提交需要，注意是否支持生成pdf文件。喜欢同一窗口实时预览的可以使用Typora，不追求实时预览可以使用vscode，并推荐安装插件:   
   1. Markdowm All in One：提供markdown的基本支持，支持生成书签，支持使用快捷键`ctrl+M`进行行间公式插入，连按两次`ctrl+M`进行行内公式插入。
   2. Markdown Preview Enhanced：原用于增强预览功能，但我主要馋它可以利用Chrome浏览器将markdown文件打印成pdf。同时它集成了很多小功能，详见[Markdown Preview Enhanced 中文文档](https://shd101wyy.github.io/markdown-preview-enhanced/#/zh-cn/)。