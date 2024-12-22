
 


 






# 1 EverEdit插件\-CHM助手：一种免费、高效的CHM手册制作方式


## 1\.1 前言


  业界制作CHM手册的工具多如牛毛，高贵的商业工具如：`HelpNDoc`、`Help+Manual`、`HelpSmith`等；号称最专业的免费CHM制作工具的`Precision Helper`，以及其他各种粗制滥造的收费或免费的CHM制作工具。  以下从两种场景来介绍发布CHM帮助的过程：


### 1\.1\.1 场景1：空白工程


  所有页面要从无到有编写。  商业软件是较好的选择，比如：HelpNDoc、Help\+Manul、HelpSmith等无一例外的都提供了强大的写作功能，用户完全可以逐个章节进行手册书写，工具栏上也提供了丰富的格式设置，写作效率好，可以输出专业的手册。


### 1\.1\.2 场景2：页面就绪


  已经有大量的手册页面(html文件)，只需要编译成chm文档。


* 不管使用商业软件还是免费软件，处理方式无非两种：
	+ 逐个编写目录，将目录与文件绑定(低价值工作)。
	+ 导入文件自动生成目录，再逐个节点调整章节顺序(低效且低价值)。


 **🕮说明**：  笔者长时间的使用过HelpNDoc、Help\+Manual、Precision Helper，对它们的专业性没有任何质疑，特别是HelpNDoc对个人用户免费，输出的文档专业范十足。但以上软件制作chm文档的效率都还存在不足，特别是在导入大量现存html页面时，需要进行大量没有意义的目录调整，且不支持批量调整，让笔者一直十分苦恼。 
## 1\.2 商业软件和免费软件优缺点分析




|  | 商业软件 | 免费软件 |
| --- | --- | --- |
| **代表软件** | HelpNDoc、Help\+Manual、HelpSmith | Precision Helper |
| **优点** | * 写作功能强大 * 格式丰富 * 输出格式多样 | 免费 |
| **缺点** | * 价格昂贵 * 导入章节无法批量调整 | * 无页面写作功能 * 导入章节无法批量调整 |


注：HelpNDoc对个人使用者倒是免费，但在生成的文档中会大量插入版权标记，这种文档是不适合做为商业软件手册发布的。


## 1\.3 探讨一种新的制作CHM的思路


### 1\.3\.1 设想1：使用免费、简单、且足够专业的笔记写作工具编写手册页面


  业界大量使用的Markdown笔记软件，是非常不错的书写手册的平台， 具有如下优点：


* Markdown**语法简单**
* **格式相对丰富**，可嵌入html做补充
* **所见即所得**(很多CHM开发工具都不具备)
* 支持**源代码格式渲染**(专业CHM工具也不一定支持)
* 支持PlantUML、Graphviz等复杂**图形和公式**工具


 **🕮说明**：  作者长期使用VNote，该软件是一款非常不错的离线markdown笔记工具，支持导出html、pdf等格式的文件，我们可以将导出的html文件用于chm文档的制作。 
### 1\.3\.2 设想2：使用免费工具将这些页面编译成CHM文档


  这个设想经过笔者长期的努力，已经成为现实，即：`EverEdit插件-CHM助手`。[下载地址](https://github.com)如下是EverEdit插件\-CHM助手的使用说明：


CHM助手(CHMEE)  简介    [作者序](https://github.com)    [插件说明](https://github.com)    [如何安装CHM助手](https://github.com)  CHM工程的组成    [工程文件(HHP)](https://github.com)    [目录文件(HHC)](https://github.com)    [索引文件(HHK)](https://github.com)  CHMEE使用说明    [步骤1：清理HTML文档](https://github.com):[CMESPEED\-楚门加速器](https://cmnspeed.com)    [步骤2：图片宽度转换相对宽度](https://github.com)    [步骤3：文字编码转换](https://github.com)    [步骤4：制作帮助文件大纲](https://github.com)    [步骤5：制作CHM工程并编译](https://github.com)  高效写作手册    [高效制作接口文档](https://github.com)    [使用Markdown工具写作手册](https://github.com)  参考    [CHM文件搜索显示为乱码或结果不全问题处理方法](https://github.com)




---


文档作者声明：本文档仅用于学习交流，未经作者许可，不得将本文档用于其他目的。Copyright © 2022\~2024 All rights reserved.






