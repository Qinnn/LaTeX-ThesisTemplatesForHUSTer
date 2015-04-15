# LaTeX-ThesisTemplatesForHUSTer
A vvvvvery rough LaTeX Thesis Template For HUSTer.

0
---
LaTeX的强悍之处不多言。此模板非常粗糙，没有封装，基于ctex宏包做了一些改动，使其满足给定的论文格式（有细微差异），以此为机会学习Git 与LaTeX，并为大家提供另外一种写论文的工具。框架已经完成，后续会维护细节内容，并补充一些实例。内容非常浅显高手请无视。

1 环境
---
使用TeX Live 2014 + WinEdt 9.0

2 基本用法
---
fork 或者直接 下载整个文件

将论文内容填入

* \Abstract_Chn.tex (中文摘要)
* \Abstract_Eng.tex（英文摘要）
* \Sect1\sect.tex (第一节)
* \Sect2\sect.tex (第二节)
*  ... (按需求添加即可)

请把main.tex设置为主文件，使用XeLaTeX编译即可。

使用XeLaTeX编译

3 参考文献
---
如果你使用EndNote请给文献加好label之后导出，然后直接copy进\Ref.bib内。

如果你不使用EndNote请按照Ref.bib内给出的格式填好你自己的参考文献。

然后按照如下顺序编译：
XeLaTeX --> BibTeX -->XeLaTeX -->XeLaTeX

4 
--- 
Titlepage纯属无聊，生成的文章从中文摘要开始符合官方要求，中文摘要之前的什么原创性声明和封面直接打印他们给的页面就可以了。

欢迎讨论
欢迎一起维护这个东西，做好封装。

Ohce Qin

qinyc@hotmail.com