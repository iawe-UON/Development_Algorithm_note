# Chap1：HTML，CSS (标题部分)
绝对磁盘路径：本地绝对路径

绝对网络路径：联网情况下，网络上的图片路径

相对路径：./当前目录，可以省略；../ 上级目录，不可以省略

\<img> 中, width height定义图像大小，px表示像素，%表示百分比

css引入样式：

行内样式：
```html
<h1 style="xxx">
```
内嵌样式：

```html
<style>
    h1{
        xxx:xxx;
        xxx:xxx;
        ...
    }
<\style>
```

外联样式：单独写一个css文件

css选择器：

元素选择器/标签选择器：
```html
 h{

 }
```
id选择器：
```html
    #hid{

    }
```
类选择器：
``` html
    .cls{
    
    }
```
优先级：id选择器>类选择器>标签选择器

无语义标签\<span>

### 超链接

```html
1.标签：
<a href="url" target="_self">
2.属性：
target:
_self:在当前界面打开
_blank:新开一个页面
3.通过对a标签进行操作来改变颜色等属性
4.text_decoration:（文本装饰）来对文本是否添加下划线进行操作
```






