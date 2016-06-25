### logstash安装
```
官方参照 ：
https://www.elastic.co/downloads/logstash
非官方参照：
http://kibana.logstash.es/content/logstash/get_start/hello_world.html
```

1.下载
> 以下安装包最好用专门的下载工具下载，因为国内网络不是很稳定，经常会下载失败
```
wget https://download.elastic.co/logstash/logstash/logstash-2.3.3.tar.gz
```
2.解压
```
tar -zxvf  logstash-2.3.3.tar.gz
```

3.运行 & 测试是否成功
```
cd logstash-2.3.3 && bin/logstash -e 'input{stdin{}}output{stdout{codec=>rubydebug}}'

```
继续在终端输入 hello word
终端输出
```bash
{
       "message" => "hello word",
      "@version" => "1",
    "@timestamp" => "2016-06-25T09:41:33.743Z",
          "host" => "ubuntu",
}
```
终端出现上面的界面，说明logstash安装成功了