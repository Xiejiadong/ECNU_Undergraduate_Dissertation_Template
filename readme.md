# ECNU Undergraduate Dissertation Template

## 华东师范大学本科生（理工科）毕业论文模板

本模版通过修改来自于 [programokey](https://github.com/programokey/ECNUUndergraduateDissertationTemplate) 的版本，主要实现了以下功能：

* 实现了 Overleaf 的支持
* 删除了一些不必要的结构
* 更新模版内容以适应**2024**年最新的论文模版要求

可以直接将这个文件全部导入至 Overleaf 使用，方便快捷，省心省力

若在本地使用，推荐安装 [TeX Live](https://www.tug.org/texlive/)（[国内镜像](https://mirrors.tuna.tsinghua.edu.cn/help/CTAN/)），搭配 [VS Code](https://code.visualstudio.com/) 的 [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) 扩展

## 模版结构

模版的主要文件内容如下所示，文章中有图片、表格和伪代码的示例，可以自己选用。
文献应用也给出了相应的示例，可以参考。

**编译请使用 XeLatex**

* main.tex 文章的主体 tex，**直接编译 main.tex 即可**
* packages_and_settings.tex 引入包和环境定义（不要动）
* inner-cover.tex 封面（不要动）
* paper_info.tex **完善基本信息**
* sign.tex 信息确认页面（不要动）
* abstract.tex **论文摘要部分**
* figures 文件夹中存放论文所需要的图片
* algorithm相关的所有 sty 用于支持伪代码
* intros/preli.tex 正文部分的示例
* simsun.ttc 宋体字体

更多关于其他 Latex 书写的细节可以参考 [programokey](https://github.com/programokey/ECNUUndergraduateDissertationTemplate) 的版本
