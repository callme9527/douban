## douban spider（python2.7）
  本程序主要使用urllib2爬取豆瓣相应标签下（如：小说）的所有书本信息，包括书名，价格，作者，国家，评分，书的图片，书的详情页等。
功能简单，主要是自己练手。大家如果有需要可以进行抓取，同时也希望大家可以帮我改进指正-》-《-！<br/>
### 用到的python库
  除标准库外，还有bs4用于解析，openpyxl用于保存信息至excel，大家可以通过pip下载。<br/>
### 用法
python douban_book.py -c 标签 <br/>
执行完毕后，错误会保存到error_urls.txt中，书本信息会保存到books.xlsx的excel表格中。<br/>
