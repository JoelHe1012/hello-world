# hello-world
# 这是一个分支
分支内容是关于markdown语法的练习

# Markdown Cheat Sheet

Thanks for visiting [The Markdown Guide](https://www.markdownguide.org)!

This Markdown cheat sheet provides a quick overview of all the Markdown syntax elements. It can’t cover every edge case, so if you need more information about any of these elements, refer to the reference guides for [basic syntax](https://www.markdownguide.org/basic-syntax/) and [extended syntax](https://www.markdownguide.org/extended-syntax/).

## Basic Syntax

These are the elements outlined in John Gruber’s original design document. All Markdown applications support these elements.

### Heading

# H1 一级标题
## H2 二级标题
### H3 三级标题

### Bold

**bold text** **粗体**

### Italic

*italicized text* *斜体*

### Blockquote

> blockquote
> 引用
### Ordered List

1. First item
2. Second item
3. Third item
4. 第一项
5. 第二项
6. 第三项(点与文字之间要有空格)

### Unordered List

- First item
- Second item
- Third item
- 显示为一个原点
### Code

`code`
`print('这是一段代码')`

### Horizontal Rule（分隔线）

---

### Link

[Markdown Guide](https://www.markdownguide.org) 链接格式

### Image 图片格式

![alt text](https://www.markdownguide.org/assets/images/tux.png)

## Extended Syntax

These elements extend the basic syntax by adding additional features. Not all Markdown applications support these elements.

### Table

| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |

|表格|表格|
|----------|-------------|
|表格|表格|

### Fenced Code Block

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

### Footnote

Here's a sentence with a footnote. [^1]

这是一个脚注。[^2]

[^1]: This is the footnote.
[^2]: 这是脚注

### Heading ID

### My Great Heading {#custom-id}

### Definition List

term
: definition

### Strikethrough

~~The world is flat.~~
~~删除线~~

### Task List

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media
- [ ] 任务清单

### Emoji

That is so funny! :joy:

(See also [Copying and Pasting Emoji](https://www.markdownguide.org/extended-syntax/#copying-and-pasting-emoji))

### Highlight

I need to highlight these ==very important words==.
== 高亮 ==

### Subscript

H~2~O
下标~1~

### Superscript

X^2^
上标^2^
