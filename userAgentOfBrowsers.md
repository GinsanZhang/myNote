#各个浏览器的userAgent
#前言
最早的流量器：[Cello](https://en.wikipedia.org/wiki/Cello_(web_browser) "Cello"),运行在window3.1。

最早支持图片和文字的浏览器：[Mosaic](https://en.wikipedia.org/wiki/Mosaic_(web_browser) "wiki") （马赛克） 由美国国家超级计算机应用中心- National Center for Supercomputing Applications (NCSA)研发。之后出现了Mozilla（相比于Mosaic支持Frame，后更名Netscape）、IE、Firefox（Gecko）、Konqueror（KHTML，linux）、Safari（webkit）、chrome（webkit）

- 1993年1月23日：Mosaic
- 1994年12月：Netscape
- 1994年：Opera
- 1995年8月16日：Internet Explorer
- 1996年10月14日：Kongqueror
- 2003年1月7日：Safari
- 2008年9月2日：Chrome
## IE
>Windows NT 6.1 就是win7

- Edge(11)

`Mozilla/5.0 (Windows NT 6.1; WOW64; Trident/7.0; SLCC2; .NET CLR 2.0.50727; .NET CLR 3.5.30729; .NET CLR 3.0.30729; .NET4.0C; .NET4.0E; Media Center PC 6.0; InfoPath.3; rv:11.0) like Gecko`

 - 10 
 
 `Mozilla/5.0 (compatible; MSIE 10.0; Windows NT 6.1; WOW64; Trident/7.0; SLCC2; .NET CLR 2.0.50727; .NET CLR 3.5.30729; .NET CLR 3.0.30729; .NET4.0C; .NET4.0E; Media Center PC 6.0; InfoPath.3)`

 - 9

`Mozilla/5.0 (compatible; MSIE 9.0; Windows NT 6.1; WOW64; Trident/7.0; SLCC2; .NET CLR 2.0.50727; .NET CLR 3.5.30729; .NET CLR 3.0.30729; .NET4.0C; .NET4.0E; Media Center PC 6.0; InfoPath.3)`

 - 8

`Mozilla/4.0 (compatible; MSIE 8.0; Windows NT 6.1; WOW64; Trident/7.0; SLCC2; .NET CLR 2.0.50727; .NET CLR 3.5.30729; .NET CLR 3.0.30729; .NET4.0C; .NET4.0E; Media Center PC 6.0; InfoPath.3)`

 - 7

`Mozilla/4.0 (compatible; MSIE 7.0; Windows NT 6.1; WOW64; Trident/7.0; SLCC2; .NET CLR 2.0.50727; .NET CLR 3.5.30729; .NET CLR 3.0.30729; .NET4.0C; .NET4.0E; Media Center PC 6.0; InfoPath.3)`

 - 5
 
`Mozilla/4.0 (compatible; MSIE 7.0; Windows NT 6.1; WOW64; Trident/7.0; SLCC2; .NET CLR 2.0.50727; .NET CLR 3.5.30729; .NET CLR 3.0.30729; .NET4.0C; .NET4.0E; Media Center PC 6.0; InfoPath.3)`

## Firefox 
 
`Mozilla/5.0 (Windows NT 6.1; WOW64; rv:49.0) Gecko/20100101 Firefox/49.0`

##Chrome

`Mozilla/5.0 (Windows NT 6.1; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/51.0.2704.63 Safari/537.36`

##safari ios

`Mozilla/5.0 (iphone;CPU iPhone OS 10_1_1 like Mac OS X)   AppleWebKit/602.2.14(KHTML, like Gecko) Mobile/14B100`

><font color="green">
>1. Gecko：Mozilla 研发的渲染引擎 </br>
>***2. KHTML:Linux 下的渲染引擎，KDE研发，在此基础上又有了webcore</br>***
>3. AppleWebKit：apple基于webcore（KHTML）的渲染引擎Webkit</br>
>4. Trident：微软的渲染引擎（MSHTML）</br>
>5. Blink：chrome的渲染引擎在webkit上fork出来的（chrome://version/ 可以查看）</br>
>6. like Gecko:是为了配合网站管理员的探测规则，为得到更好的页面开始将自己伪装成“like Gecko”</br>
></font></br>
>再后来，谷歌开发了Chrome浏览器，Chrome使用Webkit作为渲染引擎，和Safari之前一样，它想要那些为Safari编写的页面，于是它伪装成了Safari。于是Chrome使用WebKit，并将自己伪装成Safari，WebKit伪装成KHTML，KHTML伪装成Gecko，最后所有的浏览器都伪装成了Mozilla，这就是为什么所有的浏览器User-Agent里都有Mozilla。

*参考：[https://zhidao.baidu.com/question/1767408752449075980.html](https://zhidao.baidu.com/question/1767408752449075980.html "https://zhidao.baidu.com/question/1767408752449075980.html")*

[http://www.nowamagic.net/ 简明现代魔法](http://www.nowamagic.net/ "http://www.nowamagic.net/")