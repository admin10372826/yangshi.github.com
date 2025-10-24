---
title: "带内容的归档布局"
layout: archive
permalink: /archive-layout-with-content/
---

下面展示主题对常见 Markdown 元素的样式效果。

# 一级标题

## 二级标题

### 三级标题

#### 四级标题

##### 五级标题

###### 六级标题

## 引用

单行引用：

> 引用可以让重点内容更醒目。

## 表格

| 条目            | 项目   | 说明                                                         |
| --------         | ------ | ------------------------------------------------------------ |
| [John Doe](#)    | 2016   | 列表条目的说明                                               |
| [Jane Doe](#)    | 2019   | 列表条目的说明                                               |
| [Doe Doe](#)     | 2022   | 列表条目的说明                                               |

| Header1 | Header2 | Header3 |
|:--------|:-------:|--------:|
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|-----------------------------|
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|=============================|
| Foot1   | Foot2   | Foot3   |

## 定义列表

定义列表示例
:   说明定义列表的条目。

Startup
:   初创公司是一种为了寻找可重复、可扩展商业模式而设立的临时组织。

#dowork
:   由 Rob Dyrdek 与搭档 Christopher "Big Black" Boykins 提出的自我激励口号。

Do It Live
:   相关背景可参见 [Bill O'Reilly 的视频](https://www.youtube.com/watch?v=O_HyZ5aW76c "We'll Do It Live")。

## 嵌套无序列表

  * 列表项一 
    * 子项一 
      * 深层子项一
      * 深层子项二
      * 深层子项三
      * 深层子项四
    * 子项二
    * 子项三
    * 子项四
  * 列表项二
  * 列表项三
  * 列表项四

## 嵌套有序列表

  1. 列表项一 
    1. 子项一 
      1. 深层子项一
      2. 深层子项二
      3. 深层子项三
      4. 深层子项四
    2. 子项二
    3. 子项三
    4. 子项四
  2. 列表项二
  3. 列表项三
  4. 列表项四

## 按钮

给链接添加 `.btn` 类即可获得按钮样式。

## 提示框

**请注意！** 可以在段落后添加 `{: .notice}` 创建提示框。
{: .notice}

## HTML 标签

### Address 标签

<address>
  1 Infinite Loop<br /> Cupertino, CA 95014<br /> United States
</address>

### Anchor 标签（链接）

这是一个 [链接示例](http://github.com "GitHub").

### Abbreviation 标签

CSS 是 “Cascading Style Sheets” 的缩写。

*[CSS]: Cascading Style Sheets

### Cite 标签

“Code is poetry.” ---<cite>Automattic</cite>

### Code 标签

`word-wrap: break-word;` 可以避免长代码撑破布局。

### Strike 标签

用于展示 <strike>删除线文字</strike>。

### Emphasize 标签

用于显示 _斜体文字_。

### Insert 标签

用于展示 <ins>新增内容</ins>。

### Keyboard 标签

用于标识 <kbd>键盘输入</kbd>，样式类似 `<code>` 标签。

### Preformatted 标签

用于展示预格式化的大段文本。

<pre>
.post-title {
  margin: 0 0 5px;
  font-weight: bold;
  font-size: 38px;
  line-height: 1.2;
  and here's a line of some really, really, really, really long text, just to see how the PRE tag handles it and to find out how it overflows;
}
</pre>

### Quote 标签

<q>Developers, developers, developers&#8230;</q> ——Steve Ballmer

### Strong 标签

用于强调 **粗体文字**。

### Subscript 标签

H<sub>2</sub>O 中的 “2” 会被正确下沉。

### Superscript 标签

在 E = MC<sup>2</sup> 中，“2” 会显示为上标。

### Variable 标签

用于表示 <var>变量</var>。

{% include base_path %}
{% for post in site.pages %}
{% include archive-single.html %}
{% endfor %}