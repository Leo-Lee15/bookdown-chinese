# bookdown 中文范例

这是一个简单的用 **bookdown** 写中文书的例子。在使用它之前，建议您至少泛读一遍 [**bookdown** 官方文档](https://bookdown.org/yihui/bookdown)。

**Note**

> 按照谢大神的[bookdown 中文书籍范例](https://github.com/yihui/bookdown-chinese)，照猫画虎，却意外出现了编译错误，后来把preamble.tex的15到27行删掉，把index.Rmd里的 colorlinks: yes 改为 no，中文文档就华丽丽地编译出来了。
> 
>[不可挡的bookdown](http://www.pzhao.org/zh/post/inresistible-bookdown/#fn6)

本模板是修改过的版本！

感谢谢益辉大神开发的`bookdown`包和赵鹏大神的博客！


`yaml`header部分说明：
```
---
title: "麻麻说我们可以用 R Markdown 写书了"   # 标题
author: "张三"                              # 作者
date: "`r Sys.Date()`"                      #  日期 
documentclass: ctexbook                     
bibliography: [book.bib, packages.bib]
biblio-style: apalike
link-citations: yes
colorlinks: no                             # 原模板这里是“yes”，改为"no"之后才正常运行
lot: yes                                   # 是否关闭表目录，显示哪张表在哪一页
lof: yes                                   # 是否关闭图目录，显示哪幅图在哪一页
geometry: [b5paper, tmargin=2.5cm, bmargin=2.5cm, lmargin=3.5cm, rmargin=2.5cm]
site: bookdown::bookdown_site
description: "一个简单的中文书示例。"
github-repo: yihui/bookdown-chinese
#cover-image: images/cover.jpg             # 显示封面图片，不知道为什么，我的没有成功
---
```




