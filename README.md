# 基于Elasticsearch实现商品搜索
> 通过爬虫爬取的数据储存在mysql中，使用logstash将数据加载到Es中，实现拼音+汉字的模糊搜索条目
jdbc.conf为logstash的启动脚本文件；jdbc.sql是.conf文件引用的sql查询语句
