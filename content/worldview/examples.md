---
date: 2025-11-20T11:27:23+08:00
title: "A1页面"
author: 祁新
tags:
  - 技术
  - 旅行
cover:
  image: images/祁观.png
  alt: 示例封面
  relative: true
ShowReadingTime: true
ShowWordCount: true
ShowToc: true
TocOpen: true
summary: 这是一篇关于如何配置 PaperMod 头部信息的详细教程

menu:
  main:
    parent: "menu-a" # 这里的 parent 必须对应 _index.md 中定义的 identifier
    weight: 1        # 同级页面中的先后，越小越是靠前
---

你好，世界！
这是我的 **Hugo** 博客测试。

#### 嵌入原生 HTM

PaperMod 追求极致的简洁，因此它并没有内置像其他臃肿主题那样成百上千的 Shortcodes。它秉持的哲学是：“只提供最核心的工具，其他的交给你控制”。

{{< rawhtml >}}
  <div style="background-color: #fff3cd; color: #856404; padding: 15px; border-radius: 5px; border: 1px solid #ffeeba;">
    ⚠️ <strong>注意：</strong> 这是一个自定义的警告框！
  </div>
{{< /rawhtml >}}


#### 折叠内容 (collapse)

{{< collapse summary="点击查看详细日志" >}}

这里是被隐藏的内容。
可以包含 **Markdown** 语法，比如代码块：

```python

print("Hello World")

```

{{< /collapse >}}


#### 增强图片 (figure)

虽然 Markdown 自带图片标记，但 PaperMod 提供 figure 标签，让你能控制图片对齐方式、标题和尺寸。


{{< figure src="/images/祁观.png" caption="这是一张居中的图片" align="center" link="https://docs.python.org/zh-cn/3.13/tutorial/classes.html#private-variables" width="200" >}}


常用参数：
- align: center, left, right
- caption: 图片下方的灰色小字说明
- link: 点击图片跳转的链接
- target: _blank (新窗口打开)


#### 社交媒体嵌入

PaperMod 对 Hugo 内置的社交媒体 Shortcodes 做了很好的样式适配（响应式、自适应宽度）。各种嵌入按需查询。




