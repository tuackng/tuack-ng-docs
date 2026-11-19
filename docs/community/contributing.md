---
title: 贡献指南
description: 为 Tuack-NG 文档做贡献的方式与约定。
---

> [!warning] 注意
> 本文是面向 **Tuack-NG 文档** 贡献者的指南。如果您要为 **Tuack-NG 本体** 做出贡献，请参阅 [Tuack-NG 贡献指南](https://github.com/tuackng/tuack-ng/blob/master/CONTRIBUTING.md)。

本文档的建设离不开广大用户的支持，感谢您考虑为本文档做出贡献❤️！在为本文档贡献之前，请先阅读本指南。

本文档基于 [VitePress](https://vitepress.dev/) 搭建。了解 [VitePress](https://vitepress.dev/) 的用法对编写本文档很有帮助。

## 贡献准则

- 使用小写文件名

    VitePress 对 URL 链接大小写敏感，使用包含大写字母的文件名可能会出现一些问题。在命名文档和文件夹时请使用小写字母，并用`-`分割每个单词，例如：

    ``` plaintext
    example-doc.md
    example-folder/
        |- another-doc.md
    ```

- 将图片放置在仓库文件中

    插入图片时请尽量直接将源文件插入到仓库文件中，不使用额外的 CDN / 图床承载图片，以便发布文档时自动将图片等文件打包到站点上。插入的图片请放置在 `(文档目录)/image/(文档文件名)`下，例如：

    ``` plaintext
    example-doc.md
    example-doc-2.md
    image/
        |- example-doc/
        |   |- image1.png
        |   |- image2.png
        |- example-doc-2/
            |- image1.png
            |- image2.png
    ```

- 编写简单易读的文档

    在编写文档时请尽量做到简单易读。必要时可以插入图片、Mermaid 图表等便于读者理解。

- 经过格式化

    文档汉字与数字和字母间应该有空格（可以使用 VS Code 插件 AutoCorrect 自动实现此格式化），且在提交审核前应该至少使用 markdownlint 格式化一遍，否则您的 Pull Request 可能会被打回更改。

## 合并更改

您可以向本项目发起 [Pull Request](https://github.com/tuackng/tuack-ng-docs/pulls) 来合并您的更改。在发起 Pull Request 时，请简要地描述您做的更改。

更改合并以后，您可以在文档站中看到您的更改。

## 还有疑问？

您可以[加入 QQ 群](https://qm.qq.com/q/kFAubBur72)与开发者和其他用户讨论。
