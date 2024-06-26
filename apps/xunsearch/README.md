README of Xunsearch
===================
$Id$

综述
----

Xunsearch （中文名：迅搜）是一套免费开源的专业中文全文检索解决方案，简单易用而且
功能强大、性能卓越能轻松处理海量数据的全文检索。它包含后端索引、搜索服务程序和前端
脚本语言编写的开发包(称之为 SDK) 。前端和后端甚至可以分离部署在不同服务器中。一般
开发者只要在安装和设置完成后，通过提供的 SDK 包进行较为容易的二次开发即可打造出自己
的全文搜索引擎，适用于 MySQL 数据库全文检索、web站内/论坛搜索、行业门户/垂直搜索、
文档/文献检索等各种领域。

Xunsearch 底层采用 C/C++ 编写，索引设计基于著名而悠久的 [Xapian][1]，分词采用
自主研发同样也是开源的 [SCWS分词][2]，两者完美结合，理论上单个搜索库支持 40 亿条
记录。可编译运行于 Linux/FreeBSD 等各种 UNIX 类型的系统。

Xunsearch devkit SDK 理论上支持各种包含 socket 实现的脚本语言，目前我们只提供 
PHP 的实现方式，其它脚本的 SDK 往后会陆续考虑和开发，也欢迎有能力开发的人加入或
贡献相关代码。开发包代码可以运行于任何平台（包括 windows）。

Xunsearch 在确保高性能、全功能检索的基础上降低开发难度，支持字段检索、结果高亮、
字段排序、布尔语法、区间检索、聚合搜索、相关搜索、权重微调、拼音搜索、搜索建议等
专业搜索引擎具备的各项功能。

Xunsearch 全面开源，并使用最流行的开源许可协议 GPL 发布。您可以免费获取本项目的
全部源代码，并在许可条件下修改和再分发，具体参见 [COPYING](COPYING) 文件。

请关注我们的官方网站：<http://www.xunsearch.com>
在这里可以获取本项目的最新消息，和参与社区讨论和获得免费技术支持。


安装、升级
---------

请阅读 [README.install](https://github.com/hightman/xunsearch/blob/master/README.install) 文件


SDK 开发文档
-----------

请阅读 [PHP-SDK 文档](https://github.com/hightman/xunsearch/blob/master/sdk/php/README.md)


架构说明
-------

请参看 [README.arch](https://github.com/hightman/xunsearch/blob/master/README.arch)


开源捐赠
-------

我们一直在努力，我们一直想做得更好，开源事业离不开大家的支持！
[捐赠我们](http://www.xunsearch.com/site/donate)


商业、其它技术支持
----------------

为充分满足不同类型和层次的客户需求，我们在开源版本的基础上提供搜索相关的功能定制服务。
我们的技术和经验积累将为您极大程度地节约开发成本和时间。

具体请访问我们的支持页面：<http://www.xunsearch.com/support/>


[1]: http://xapian.org/
[2]: http://www.xunsearch.com/scws/
