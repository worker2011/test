---
title: hexo-sliding-spoiler演示
date: -24 18:17:49
tags: "测试"
mathjax: true
---

{% spoiler 可以折叠词 %}


content


{% endspoiler %}


{% spoiler 也支持Markdown语法 %}


~~删除线~~


**加粗**


*斜体*


### 标题党也行
图片![图片](/img/g.jpg)
和[链接](https://github.com/fletchto99/hexo-sliding-spoiler)也都支持
1. 有序序列
- 无序序列


当然，最主要的还是代码块，这个也是支持高亮的（如果你有用）
```python
print("Hello World!")
```
{% endspoiler %}

{% spoiler MathJax也支持（如果你博客支持它就支持！） %}

$2 ^ {10} = 1024$

{% endspoiler %}

