##### 标题

```bash
# h1
## h2
### h3
#### h4
##### h5
###### h6
####### h7      // 错误代码
######## h8     // 错误代码
######### h9    // 错误代码
########## h10  // 错误代码
```

##### 分级标题

```undefined
一级标题
======================
二级标题
---------------------
```

##### TOC

```json
根据标题生成目录
[TOC]
```

##### 引用

```undefined
> hello world!
```

##### 行内标记

```go
用 ` 标记代码块将变成一行

标记之外`hello world`标记之外
```

##### 代码块

~~~xml
用```生成块

```
<div>   
    <div></div>
    <div></div>
    <div></div>
</div>
```
~~~

##### 插入链接

```ruby
(内链式)
注：{:target="_blank"}跳转方式兼容性一般 ，多数第三方平台不支持跳转
[百度1](http://www.baidu.com/" 百度一下"){:target="_blank"}   
```

```csharp
(引用式)
[百度2][2]{:target="_blank"}
[2]: http://www.baidu.com/   "百度二下"
```

##### 插入图片

```json
[图片上传失败...(image-90880b-1542510791300)]
```

##### 插入图片带有链接

```csharp
[[图片上传失败...(image-f83b77-1542510791300)]](http://www.baidu.com){:target="_blank"}       // 内链式

[[图片上传失败...(image-4dc956-1542510791300)]][5]{:target="_blank"}                      // 引用式
[5]: http://www.baidu.com
```

##### 视频插入

```xml
多数第三方平台不支持插入<iframe>视频
<iframe height=498 width=510 src='http://player.youku.com/embed/XMjgzNzM0NTYxNg==' frameborder=0 'allowfullscreen'></iframe>
```

```csharp
[[图片上传失败...(image-49aefe-1542510791300)]](http://v.youku.com/v_show/id_XMjgzNzM0NTYxNg==.html?spm=a2htv.20009910.contentHolderUnit2.A&from=y1.3-tv-grid-1007-9910.86804.1-2#paction){:target="_blank"}
```

##### 序表

```undefined
(有序)
注：序列.后 保持空格
1. one
2. two
3. three
```

```undefined
(无序)
* one
* two
* three
```

```undefined
(序表嵌套)
1. one
    1. one-1
    2. two-2
2. two 
    * two-1
    * two-2
```

```csharp
(序表嵌套代码块)
注：换行+两个Tab
* one

    var a = 10;     // 与上行保持空行并 递进缩进
```

##### 任务列表

```css
兼容性一般 要隔开一行
这是文字……

- [x] 选项一
- [ ] 选项二  
- [ ]  [选项3]
```

##### 表格

```ruby
 : 代表对齐方式 ,** : 与 | 之间不要有空格**
|    a    |       b       |      c     |
|:-------:|:------------- | ----------:|
|   居中  |     左对齐    |   右对齐   |
|=========|===============|============|
```

![特殊表格](https://upload-images.jianshu.io/upload_images/6912209-46aac2b114b995ec.png?imageMogr2/auto-orient/strip|imageView2/2/w/1113/format/webp)

在线生成HTML代码 [Tables Generator](http://www.tablesgenerator.com/) 

##### 语义标记

| 描述      | 效果 | 代码            |
| --------- | ---- | --------------- |
| 斜体      |      | *斜体*          |
| 斜体      |      | _斜体_          |
| 加粗      |      | **加粗**        |
| 加粗+斜体 |      | ***加粗+斜体*** |
| 删除线    |      | ~~删除线~~      |
| 斜体      |      | <i>斜体</i>     |
| 强调      |      | <em>强调</em>   |
| 键盘文本  |      | kbd>Ctrl</kbd>  |
| 下标      |      | Z<sub>a</sub>   |
| 上标      |      | Z<sup>a</sup>   |



https://www.jianshu.com/p/b03a8d7b1719