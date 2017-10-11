## markdown基本语法
> markdown是一种轻量级标记语言，创始人为约翰·格鲁伯。它允许人们“使用易读易写的纯文本格式编写文档，然后转换成有效的XHTML(或者HTML)文档”。       ---摘自维基百科

### 标题
在标题内容加上不同数量的#对应不同级别的标题

```markdown
# 一级标题
## 二级标题
### 三级标题
```
### 引用
用只需要在被引用的内容段落开头加上右尖括号('>')即可。
```markdown
> 引用内容
```
### 水平分割线
使用3个或以上的星号、下划线、短横线实现
```markdown
***
_ _ _
- - -
```

### 图片
```markdown
![图片名](图片地址)
```
![滑稽](http://image.coolapk.com/apk_logo/2017/0626/ic_launcher-web-for-103638-o_1bjh782kk1sn61ue9nh9vt41vf9q-uid-543424.png)

### 强调
```markdown
*斜体强调*
**粗体强调**
```
### 链接
```markdown
[链接名称](网址,标题)

[链接名][链接代号]
[链接代号]: 链接地址 "链接标题"
[link][1]
[1]: http://www.***.com "链接标题"

直接展示<链接名>
```
### 列表
```markdown
无序列表*加空格
 * list1
 * list2

有序列表
 1. list1
 2. list2
 ```

### 表格
```markdown
Item     | Value
-------- | ---
Computer | $1600
Phone    | $12
Pipe     | $1
```
