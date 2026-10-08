# Competitive Programmer's Handbook / 竞赛程序员手册（简体中文版）

本仓库是 Antti Laaksonen 所著 *Competitive Programmer's Handbook* 的简体中文 AI 翻译稿，沿用官方 LaTeX 源码的章节组织和排版结构。全书前言及 30 章均已翻译，C++ 代码、数学公式、表格、插图与编号均予以保留。

原作者：Antti Laaksonen  
原版：Draft July 3, 2018  
中文翻译：ChatGPT  
中文版本并非作者发布的官方译本；如有歧义，以英文原文为准。

## 上游项目

- 官方源码仓库：https://github.com/pllk/cphb
- 原版 PDF：https://cses.fi/book/book.pdf
- 原书页面：https://cses.fi/book/

本仓库基于上述官方源码制作。翻译过程中未调用第三方翻译 API，也未使用本地翻译模型。

## 仓库内容

- `book.tex`：主文件。
- `preface.tex`：前言及中文版说明。
- `chapter01.tex`—`chapter30.tex`：全部 30 章中文源码。
- `list.tex`：参考文献；为便于检索，书目元数据保留原文。
- `TERMS.md`：中英术语对照表。
- `TRANSLATION_STATUS.md`：翻译、审校与排版验证状态。
- `book.pdf`：由本仓库源码生成的简体中文 PDF。

## 编译

本书使用 `ctexbook`、XeTeX 兼容字体与 TikZ。可使用支持 XeLaTeX 的完整 TeX 发行版编译：

```sh
xelatex book.tex
xelatex book.tex
xelatex book.tex
```

多次编译用于生成完整目录、交叉引用和 PDF 书签。也可以使用兼容 XeTeX 的 Tectonic 环境。

## CSES 题库

CSES 题库收录了一系列算法竞赛题目，可用于练习本书介绍的技术。

https://cses.fi/problemset/

## 许可证

原书采用知识共享署名-非商业性使用-相同方式共享 4.0 国际许可协议（Creative Commons BY-NC-SA 4.0）。本中文翻译稿依照同一许可协议发布，并保留原作者署名。

## 其他版本

Springer 出版的纸质书《Guide to Competitive Programming》以本书为基础。此外还有俄文版《Олимпиадное программирование》（Olympiad Programming）和韩文版《알고리즘 트레이닝: 프로그래밍 대회 입문 가이드》。

## 翻译与校验说明

译稿采用中国大陆算法竞赛领域常用术语。全部 `lstlisting` 代码块均与官方源码逐块校验一致；章、节、LaTeX 环境及插图结构也已自动比对，并完成全书逐页视觉检查。
