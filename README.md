# wechat-spider# sougou_wechat_crawler

基于Selenium WebDriver搜狗微信公众号爬虫
主要功能是根据输入的关键词爬取最新的文章，包括标题，简介，作者，上传时间等内容。
通过webdriver解决搜狗微信的反扒机制，直接使用浏览器进行爬虫，虽然效率比较低，但是实现起来难度小，适合轻量级的爬虫。

 注：如果搜狗微信没有登录只能默认爬取10页，登录后才能查任意次数

最后采用输出Json文件或CSV文件的方式，以达到进行后续存储等工作的目的。

**详细代码说明请参考注释**

使用：keyword 修改搜索关键词，修改关键词运行即可。