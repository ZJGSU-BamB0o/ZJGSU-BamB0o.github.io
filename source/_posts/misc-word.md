---
layout: post
title: word隐写研究
date: 2021-05-16
tags: jekyll_first_start_misc 
---

# docx小结
这个docx隐写感觉也没有什么花头了，个人认为，不过是三个。

记得上一篇博客说过，这些docx,ppt什么的全部都是压缩包，准确来说是zip压缩包，通过某种手法显示为了我们看到的样子

## docx的图片隐藏


 

 <div  align="center">
<img src="/images/11.png"/>
</div>

 

 

 

 因为是压缩包，所以这里面的所有字符都是经过哈夫曼压缩过的，用strings这种命令是绝对解析不出来的。
 <div  align="center">
<img src="/images/2.png"/>
</div>
 

但是看到docx这种题目还是会让人想起那个透明字符和隐藏文字给人带来的绝望。最好都要试一试。


  <div  align="center">
<img src="/images/3.png"/>
</div>

 <div  align="center">
<img src="/images/4.png"/>
</div>
 这个word的图片全部隐藏在这个文件夹下面




word/media  路径

 

 

 


这个docx，我觉得鬼才能看出来里面的flag藏在哪里。

但是把这个docx换成zip形式，里面的所有文件都将会一览无遗。个人猜测是类似于编程化实现的Latex编辑PDF一样。

在这里插入图片描述可能是把docx先做好再把这张图片塞进去做出来的题干吧。
个人认为这样塞进去的图片不会在docx中显示。
 <div  align="center">
<img src="/images/5.png"/>
</div>


 <div  align="center">
<img src="/images/6.png"/>
</div>

  <div  align="center">
<img src="/images/7.png"/>
</div>
 

 

## 还有就是白色字符
 

这个一般ctrl+F是可以搜出来的，雕虫小计罢了。



## word隐藏文字选项

 <div  align="center">
<img src="/images/8.png"/>
</div>
