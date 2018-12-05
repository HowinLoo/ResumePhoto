# Resume modified by Later

### 添加个人信息栏
* **相片（144×192）**
* 姓名
* 求职意向
* 微信
* 电话
* 邮箱

### 其他特点
* 扁平化图标替代文字
* 黑字白底，简单直观
* 添加了图片功能

### 个人想法
一直都是用resume-zh_CN.tex直接生成pdf直接投简历的，但是一直在纠结加上相片这件事情上，还跟别人开玩笑说打印出来直接贴一张就可以了。最后经过多次的尝试，作为一个LaTeX知识一般的人，终于将相片加进去了，主要是使用figure（图片）、minipage（分栏）、tabular*（表格）排出来的。后来想改写一下resume.cls文件的函数的，添加一个信息头函数即可，实在没看懂怎么写.cls里面的函数。

### 宇宙使用指南
* Fork → git clone
* WinEdt7.0 → 打开 → modified\_by_Later.tex → **编码：UTF-8**（不然会乱码）
* **编译方式XeLaTeX** → 查看[modified\_by_Later.pdf](https://raw.githubusercontent.com/HowinLoo/Resume_ModifiedByLater/master/modified_by_Later.pdf)
* [选用其他图标](http://mirrors-wan.geekpie.club/CTAN/fonts/fontawesome/doc/fontawesome.pdf)


### 参考引用
* [billryan/resume](https://github.com/billryan/resume)
* [HereChen/resume](https://github.com/HereChen/resume)