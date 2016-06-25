### marvel2.x安装
```
官方参照 ：
https://www.elastic.co/downloads/marvel
```
> marvel可以单独在Elasticsearch安装，也可以和Kibana都一起安装，

1.Elasticsearch安装marvel
```bash
bin/plugin install license
bin/plugin install marvel-agent
```
2.Kibana安装marvel
```bash
bin/kibana plugin --install elasticsearch/marvel/latest
```

3.启动Elasticsearch和Kibana
```bash
bin/elasticsearch
bin/kibana

```
4.浏览器输入http://localhost:5601/app/marvel
![img](https://github.com/yuexing0921/ELK/blob/master/img/init-runing-marvel.png)
出现上面的界面，说明marvel安装成功了


## [回到主页](https://github.com/yuexing0921/ELK/blob/master/README.md)