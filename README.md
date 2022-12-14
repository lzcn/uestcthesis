# 电子科技大学学位论文 $\LaTeX$ 模板

[![GitHub release](https://img.shields.io/github/release/lzcn/uestcthesis/all.svg)](https://github.com/lzcn/uestcthesis/releases/latest)
[![GitHub commits](https://img.shields.io/github/commits-since/lzcn/uestcthesis/latest.svg)](https://github.com/lzcn/uestcthesis/commits/master)
[![Build](https://github.com/lzcn/uestcthesis/workflows/build/badge.svg)](https://github.com/lzcn/uestcthesis/actions)

电子科技术大学论文 $\LaTeX$ 模板，基于[ustctug/ustcthesis](https://github.com/ustctug/ustcthesis/)项目，并参考
《[电子科技大学研究生学位论文撰写规范（2022 年 1 月修订）](https://gr.uestc.edu.cn/xiazai/114/3917)》的要求编写。

## 编译文档

- 编译模板的使用说明文档 `uestcthesis-doc.pdf`：

  ```bash
  latexmk -xelatex uestcthesis-doc.tex
  ```

- 编译论文 `main.pdf`：

  ```bash
  latexmk -xelatex main.tex
  ```

- 如需清理论文编译过程中的临时文件，可以：

  ```bash
  latexmk -c
  ```

- 以上编译过程也可以用 `make` 工具：

  ```bash
  make doc        # 编译生成 uestcthesis-doc.pdf
  make main       # 编译生成论文 main.pdf
  make clean      # 删除编译过程中生成的临时文件
  ```

## 反馈问题

如果发现模板有问题，请按照以下步骤操作：

1. 阅读学校的标准，判断是否符合学校的要求；
2. 阅读 [常见问题 FAQ](https://github.com/lzcn/uestcthesis/wiki/常见问题)；
3. 将 TeX 发行版和宏包升级到最新，并且将模板升级到 Github 上最新版本，
   查看问题是否已经修复；
4. 在 [GitHub Issues](https://github.com/lzcn/uestcthesis/issues)
   中搜索该问题的关键词；
5. 在 [GitHub Issues](https://github.com/lzcn/uestcthesis/issues)
   中提出新 issue，并回答以下问题： - 使用了什么版本的 TeX Live / MacTeX / MiKTeX ？ - 具体的问题是什么？ - 正确的结果应该是什么样的？ - 是否应该附上相关源码或者截图？

## 更多资料

- [LaTeX 新手入门指南](https://github.com/lzcn/uestcthesis/wiki/新手指南)
- [常见问题 FAQ](https://github.com/lzcn/uestcthesis/wiki/常见问题)
- [参与开发](https://github.com/lzcn/uestcthesis/wiki/参与开发)
