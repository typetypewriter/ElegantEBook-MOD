仿照ElegantBook的typst模板，直接下载仓库代码即可，可以查看pdf查看具体说明。

文件结构

\library                 库文件夹
\library\parameter.typ   控制文档的参数
\library\function.typ    文档所用的函数
\library\template.typ    文档模板文件
\library\zself.typ       用户自己添加的函数、
\figure                  图像文件夹
\content                 内容文档文件夹 （注意每个文件头部添加 #import "../library/template.typ": *）
\main.typ                主文件（编译使用这个文件）
\refs.bib                参考文献文档
