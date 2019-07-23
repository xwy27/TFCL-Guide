# TFCL-Guide

本仓库为编写 **TensorFlow 官方文档中文化协助手册**(Guide for TF Community Localization) 而创建。

**TensorFlow 官方文档中文化协助手册**提供了参与 TensorFlow 官方文档中文化的快速上手指南和一些常见问题的解答。

## 本文档规范

- 资源文件

  静态资源一律存储在 `assets` 文件夹下，命名不冲突即可(*具体有待修改*)

- Markdown 规范

  - 标题

    每级标题使用**一行空行**与上下文隔开

    ```
    # title one

    ## title two

    ### title three
    ```

  - 无序列表

    无序列表使用**一行空行**与上下文隔开；无序列表项与其所属内容**空一行**，使用**两个空格**缩进。

    ```
    content

    - item

      content

    - item

      content

    content
    ```

  - 有序列表

    有序列表使用**一行空行**与上下文隔开；有序列表项与其所属内容**空一行**，使用**四个空格**缩进；列表项序号从 1 开始递增

    ```
    content

    1. item

        content

    2. item

        content

    content
    ```
  
  - 语言规范

    - 中文与英文单词使用空格隔开
    - 中文与数字使用空格隔开
    - 全角符号(中文符号)和英文单词之间无需使用空格隔开
