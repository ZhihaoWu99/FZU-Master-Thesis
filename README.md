# FZU-Master-Thesis
福州大学研究生毕业论文LaTex模板

# 说明
福州大学研究生毕业论文模板，也可用于福州大学本科毕业论文撰写。

# 使用
使用本项目需要先安装Tex环境，例如[TeXLive](https://tug.org/texlive/)，请选择XeLaTex引擎进行编译，具体LaTex指令请参考原[电子科技大学项目]((https://github.com/bdebye/thesisuestc))。
编译`main.tex`文件即可生成PDF。也可以直接使用Oveleaf的在线Tex环境以更方便地撰写毕业论文。

注意事项：
- 封面请根据当年的学校和学院的具体通知下载最新的Word模板，在Word中完成编辑后导出并覆盖本项目`pics`目录下的`titlepage.pdf`，随后编译即可替换论文封面。
- 请先选择对应的学位类型，`main.tex`文件中首行`\documentclass[engmaster]{thesis}`中的`engmaster`（工程硕士）可以替换为`bachelor`（学士），`master`（硕士）、`promaster`（专业硕士）、`doctor`（博士）和`engdoctor`（工程博士），可以在`thesis.cls`文件中搜索相关字段修改或添加更多选项。
- 使用Overleaf注意在项目Menu中的Compiler选择XeLaTex，需要上传缺失的字库文件（如ariblk, simsun, simhei等，保存在Fonts.zip中，解压到根目录下即可）。
- 导出的最终PDF文件和Word模板导出的PDF可能存在差异（例如每页的字数），但学校似乎没有对此做严格要求，组内已有多届硕士博士用该模板顺利毕业，如果比较担心可以采用Word模板。

# 致谢
该论文模板修改自[电子科技大学博士毕业论文模板](https://github.com/bdebye/thesisuestc)，[FZUThesis](https://github.com/chenzl23/FZUThesis)，感谢[肖顺鑫博士](https://github.com/Xiaoshunxin)、[陈赵亮博士](https://github.com/chenzl23)、[卢杰龙博士](https://github.com/long319)对该模板的修改和改进做出的贡献。
