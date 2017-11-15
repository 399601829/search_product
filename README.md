# 基于Elasticsearch实现商品搜索：
> 通过爬虫爬取的数据储存在mysql中，使用logstash将数据加载到Es中，实现拼音+汉字的模糊搜索条目

-- jdbc.conf为logstash的启动脚本文件；jdbc.sql是.conf文件引用的sql查询语句

# 搜索效果：
> ![Image text](http://upload-images.jianshu.io/upload_images/79038-40d5b93969e972bd.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/700)

# 具体介绍：
http://www.jianshu.com/p/febd2b8c6f61
