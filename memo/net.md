# Net

## url区分大小写吗？

网址的基本结构是：[协议]://[域名]/[路径]

协议和域名部分不分大小写。路径部分是否区分大小写则不一定，要看具体网站后台是如何实现的。

如果网址只是给机器使用的话，可以不用计较是否大小写。但实际上难免会遇到要将网址通过手工输入到地址栏的情况（比如将印刷的地址抄写到浏览器中访问）。为了易用性的考虑，在条件允许的情况下应该尽可能的不区分大小写。如果需要区分，则尽可能要对不同写法的地址进行重定向。知乎在这一点上就做得不是很好，比如这个问题如果通过 