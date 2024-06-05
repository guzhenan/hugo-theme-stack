+++
author = "G"
title = "Markdown语法指南"
date = "2024-06-04"
description = "Markdown常用命令集"
tags = [
    "markdown"
]
categories = [
    "开发工具"
]
+++
## 标题
```markdown
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
```
## 强调

```markdown
*斜体*
_斜体_

**加粗**
__加粗__
```
## 列表

### 无序列表
```markdown
* 项目 1
* 项目 2
  * 子项目 2.1
  * 子项目 2.2
+ 项目 3
- 项目 4
```
### 有序列表
```markdown
1. 第一项
2. 第二项
3. 第三项
   1. 子项目 3.1
   2. 子项目 3.2
```
## 链接
```markdown
[这是一个链接](http://example.com)
```
## 图片
```markdown
![名称](https://markdown-here.com/img/icon256.png)
```
## 引用
```markdown
> 这是一个引用。
>> 这是一个嵌套的引用。
```
## 代码
### 行内代码
使用反引号 ` 表示行内代码。
```markdown
这是 `行内代码` 示例。
```
### 代码块
使用三个反引号 ``` 或缩进 4 个空格表示代码块。
```python
三个反引号python
def hello():
    print("Hello, World!")
```
## 表格
使用 | 分隔表格的不同列，使用 - 创建表头。
```markdown
| 头1 | 头2 | 头3 |
|---|---|---|
| 单元格1 | 单元格2 | 单元格3 |
| 单元格4 | 单元格5 | 单元格6 |
```
## 分割线
```markdown
---
***
___
```
## 任务列表
```markdown
- [ ] 未完成的任务
- [x] 已完成的任务
```