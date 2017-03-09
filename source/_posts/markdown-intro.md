---
title: Markdown——入门指南
date: 2015-01-12 13:26:05
tag: 'markdown'
categories: '前端'
---

### 1. 斜体和粗体

使用 `*斜体* 和 **粗体**` 分别表示斜体和粗体。

示例：

这是 *斜体*，这是 **粗体**。

### 2. 分级标题

- 分级标题用法

```

这是一个一级标题
===

这是一个二级标题
---

### 这是一个三级标题
```

示例：

这是一个一级标题
===

这是一个二级标题
---

### 这是一个三级标题


`注：# H1, ## H2, ### H3...，效果同上`

### 3. 外链接

使用 `\[描述](链接地址)` 为文字增加外链接。

示例：

这是去往 [本人博客](http://ghosertblog.github.com) 的链接。

### 4. 无序列表

使用 `*，+，-` 表示无序列表。

```
* 无序列表项 一
或
+ 无序列表项 二
或
- 无序列表项 三

```

示例：

+ 无序列表项 一
+ 无序列表项 二
+ 无序列表项 三

### 5. 有序列表

使用数字和点表示有序列表

```
1. 有序列表项 一
2. 有序列表项 二
3. 有序列表项 三

```

示例：

1. 有序列表项 一
2. 有序列表项 二
3. 有序列表项 三

### 6. 文字引用

使用 > 表示文字引用。

示例：

> 野火烧不尽，春风吹又生。

### 7. 行内代码块

使用 \`代码` 表示行内代码块。

示例：

让我们聊聊 `html`。

### 8.  代码块

使用 四个缩进空格 表示代码块。

示例：

    这是一个代码块，此行左侧有四个不可见的空格。

### 9.  插入图像

使用 \!\[描述](图片链接地址) 插入图像。

示例：

![我的头像](https://www.zybuluo.com/static/img/my_head.jpg)

# Cmd Markdown 高阶语法手册

### 1. 标签分类

在编辑区任意行的列首位置输入以下代码给文稿标签：

标签： 数学 英语 Markdown

或者

Tags： 数学 英语 Markdown

### 2. 删除线

使用 ~~ 表示删除线。

~~这是一段错误的文本。~~


### 3. 加强的代码块

支持四十一种编程语言的语法高亮的显示，行号显示。

只是代码示例：

```
$ sudo apt-get install vim-gnome
```

Python 示例：

```python
@requires_authorization
def somefunc(param1='', param2=0):
    '''A docstring'''
    if param1 > param2: # interesting
        print 'Greater'
    return (param2 - param1 + 1) or None

class SomeClass:
    pass

>>> message = '''interpreter
... prompt'''
```

JavaScript 示例：

``` javascript
/**
* nth element in the fibonacci series.
* @param n >= 0
* @return the nth element, >= 0.
*/
function fib(n) {
  var a = 1, b = 1;
  var tmp;
  while (--n >= 0) {
    tmp = a;
    a += b;
    b = tmp;
  }
  return a;
}

document.write(fib(10));
```

