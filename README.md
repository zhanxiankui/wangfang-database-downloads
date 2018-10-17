# wangfang-database-downloads

**这是万方数据库的爬虫文件，写了大半年了，我是使用学校的ip免费登录的，所以没有账号验证等什么鬼。**

这个爬虫，我写了二部分，一部分是爬取下面图片的摘要，关键字，作者等信息，写入excel文件中。

![万方信息.png](https://upload-images.jianshu.io/upload_images/4976516-dc214cd9a91b7650.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

另外一个是下载万方数据库的文献，这里面主要是链接地址的获取，它是js动态生成的文件，需要正则表达式获取到相关的参数，在函数生成链接。

**具体的细节看下面的博客,我以前写的，有时间准备改善一下code**

[python下载万方数据库文献](https://www.jianshu.com/p/134530b46a65)

>希望大家多多关照，喜欢就start一下。
