# 兰州大学本科生（学士学位）LaTeX模板

## 最最新更新

对模板字号进行修改
对英文 中文摘要顺序进行修改
以上修改均以Pull request的形式给出，可参考该[页面](https://github.com/VealM/LZUthesis2020/pull/2)与摘要页页码编号[修正](https://github.com/VealM/LZUthesis2020/pull/7)的git比较

### 目前存在的问题

未能实现类似word的宋体伪加粗效果，具体描述参考该[页面](https://github.com/VealM/LZUthesis2020/issues/4)

是否有必要实现图表目录合并？具体描述及可能的解决方案参考该[页面](https://github.com/VealM/LZUthesis2020/issues/5)

友情推荐兰大物理系余航大佬的[20模板](https://github.com/yuhlzu/LZUThesis2020)，虽然不认识他，但听说是编程经验与水平极高（远远高于我的大佬）。所以品质有保障，大家可以根据需要选择对应模板。
## 最新更新

最新修改于2020/4/24。根据兰州大学官方模板要求，对目录页不再进行编页码，仅对摘要页用罗马数字编页码。

涉及修改的文件为[LZUthesis.cls](LZUthesis.cls)及[template.tex](template.tex)。考虑到可能有同学在此之前已下载模板，这里也以pull request的方式贴心给出[修改部分](https://github.com/VealM/LZUthesis2020/pull/1/files)
## 原始版本

根据[2020最新本科生毕业论文模板](2020兰州大学本科生毕业论文模板.docx)改编自[LZUThesis2017](https://github.com/suchot/LZUThesis2017)
特别致谢LZUThesis2017作者suchot

移步[LZUThesis2020码云仓库](https://gitee.com/VealM/LZUthesis2020)获取更加稳定的国内下载速度

## 使用方法

推荐使用 texlive + texstudio

- 1 通过texstudio打开[template](template.tex)文件，进行毕业论文主体写作

- 2 推荐使用bib进行文献管理，用文本编辑器打开[database.bib](bib/database.bib)，插入文献引用(可通过谷歌学术获取)。

- 3 编译流程为
    - xelatex template.tex(F5) 
    - bibtex template.aux(F8)
    - xelatex template.tex(F5)

补充说明:
第一步编译后会在同级文件夹下生成template.aux，使用texstudio打开(文件类型选择all files)，按F8编译(或下拉悬浮栏的Tools找到Bibliography)。
之后需要再对template.tex进行编译，才能看到正确的文献引用。

## 具体使用方法

参考由suchot撰写的[主题介绍](主题介绍Thesis.pdf)，内容十分详尽，或移步他的代码仓库[LZUThesis2017](https://github.com/suchot/LZUThesis2017)

希望这个更新的模板能够为20毕业生减轻一点负担~
