学习使我快乐！

"Some_Script" 
# 前言
虽然19年6月毕的业，但工作也有半年多了，期间陆陆续续写了一些小脚本or轮子。也算是为了能正视自己，就厚着脸皮搬上来吧。希望某一天也能像各位大神一样写出好用的工具

2019.7.26

# 说明
还有一些脚本也不知道存哪儿了。。。。

后续还有写一些能复用的脚本的话，也都传到这儿吧！

持续更新……
## [awvs2.0](https://github.com/GuoKerS/Some_Script/tree/master/awvs2.0)
一个awvs11扫描器的辅助脚本，一键添加或删除扫描任务（在原脚本基础上增加了多线程）、增加了支持6种不同的扫描策略（高风险漏洞扫描、弱密码扫描、仅爬行、XSS扫描、SQL扫描、全扫描）

## [gov_spider](https://github.com/GuoKerS/Some_Script/tree/master/gov_spider)
当时是想做个乖宝宝，想着做一个模拟百度搜索引擎访问本省内的gov站点，用来测试是否有黑产用这类网站做劫持哈哈哈。
## [K01](https://github.com/GuoKerS/Some_Script/tree/master/K01)
在HW时做的防守方，每天都要从设备上拉取日志，然后K01（网络攻击阻断系统）的日志提取有限制（一次最多50条），于是分析了K01拉取日志时的请求，写了个小脚本方便自己搞报告。
## [proxy_spider(代理中转)](https://github.com/GuoKerS/Some_Script/tree/master/proxy_spider)
(目录的名称是错滴哈哈，当时是和爬虫一块写在同一个目录下)造的一个轮子，从网上找了好多大佬的源码进行学习，终于能勉强用了。原理贼简单 监听1080-》接收发送到1080的HTTP请求存到变量A（连接1） -》随机取一个爬到的代理并连接-》发送变量A到建立的连接中（连接2）-》将HTTP返回包存到变量B -》将变量B返回给连接1
## [Heartbleed2.0（搜集信息）](https://github.com/GuoKerS/Some_Script/tree/master/Heartbleed2.0)
初入公司，帮着公司渗透大佬打杂，写的一个心脏出血漏洞的循环利用小脚本，根据官方poc做了一些调整，增加两个参数、去除偏移地址和非ascii字符等等。用来做信息搜集。
## [wam（网站连通性监测）](https://github.com/GuoKerS/Some_Script/tree/master/wam)
当时公司有要求对客户站点的连通性进行监测，因此写了这么一个小脚本，支持微信和邮箱告警。
## [ssh（批量登陆+切换root 执行命令）](https://github.com/GuoKerS/Some_Script/tree/master/ssh)
当时在给客户安装防护软件，由于大部分（大约2000台，但实际只用这个脚本装了一小部分而已）机器都是Linux系统而且说没使用运维管理类的软件（实际上有！！！保xin持tai微bao笑zha），需要人工登陆后切换至root执行安装命令。因此试着写了这个脚本。


