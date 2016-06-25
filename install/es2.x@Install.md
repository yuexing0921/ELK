### elasticsearch安装
```
官方参照 ：
https://www.elastic.co/downloads/elasticsearch
https://www.elastic.co/guide/en/elasticsearch/reference/current/_installation.html
```

1.下载
> 以下安装包最好用专门的下载工具下载，因为国内网络不是很稳定，经常会下载失败
```
wget https://download.elastic.co/elasticsearch/release/org/elasticsearch/distribution/zip/elasticsearch/2.3.3/elasticsearch-2.3.3.zip
```

2.解压
```
unzip elasticsearch-2.3.3.zip
```

3.运行
```
cd elasticsearch-2.3.3 && bin/elasticsearch  -d 

```

> 说明：bin/elasticsearch  -d 是代表在后台执行

4.测试是否运行成功
```
curl localhost:9200
```

```
{
  "name" : "Sepulchre",
  "cluster_name" : "elasticsearch",
  "version" : {
    "number" : "2.3.3",
    "build_hash" : "218bdf10790eef486ff2c41a3df5cfa32dadcfde",
    "build_timestamp" : "2016-05-17T15:40:04Z",
    "build_snapshot" : false,
    "lucene_version" : "5.5.0"
  },
  "tagline" : "You Know, for Search"
}

```
到这里elasticsearch安装已经成功

### [kibana 4.5.1安装教程](https://github.com/yuexing0921/ELK/blob/master/install/kibana4.x@Install.md)
### [logstash 2.3.3安装教程](https://github.com/yuexing0921/ELK/blob/master/install/logstash2.x@Install.md)