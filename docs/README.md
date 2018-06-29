# 用作 Pages 根目录


吐槽点：CSDN 现在注册一个新账户都需要必须关注公众号了（通过这个操作，它至少为自己的公众号增加了一个关注，而且获取了一个真实的电话号码，看起来是没有问题的，但是对用户体验来说，🙃），真是无耻到无敌，要不是为了引流，我真的不愿意注册这种垃圾网站。

本文中描述、实现使用 GitHub Pages 来创建自己的网站，并且使用 Gitment 功能实现评论功能。

1. 注册 GitHub

2. 创建项目 wahwoo.github.io（真实过程中请替换你自己的网站，因为我最终是要打算绑定，www.wahwoo.com 域名，所以需要起一个这样的域名）

3. 在项目上创建 docs 文件夹， 因为之后要讲所有的文档都绑定到这个文件夹下

![](https://ws4.sinaimg.cn/large/006tKfTcly1fsscvnqdznj30ro0ken1g.jpg)

4. 转到 https://github.com/yourname/wahwoo.github.io/settings 开启 Pages

![](https://ws3.sinaimg.cn/large/006tKfTcly1fssey38s6lj30kc0efdit.jpg)

5. 添加自己的域名到 Custom Domain 中，具体的过程，参看更多可以参考，https://help.github.com/articles/using-a-custom-domain-with-github-pages/


这一步需要注意的是，如果使用原来的 GitHub 给定的域名的话，默认就是支持 HTTPS 的，如果绑定了自定义的域名的话，需要等待官方为你开启 HTTPS。

要开启域名解析和 HTTPS 可以参考，https://help.github.com/articles/troubleshooting-custom-domains/#https-errors

这里直接将域名的解析结果截图分享。

![](https://ws2.sinaimg.cn/large/006tKfTcly1fssf9f7dchj311h08hgnc.jpg)

配好上面的图之后，会得到提示  Not yet available for your site because the certificate has not finished being issued.
Please allow 24 hours for this process to complete. (www.wahwoo.com) ，安静的等待就可以了，当然不需要24个小时，然后再来点击开始 HTTPS 就可以了。

6. 打开网址 www.wahwoo.com 解析过来的网站就可以打开了。

![](https://ws1.sinaimg.cn/large/006tKfTcly1fssfeg25eyj30n806jwf4.jpg)
