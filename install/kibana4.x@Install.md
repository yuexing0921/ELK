### kibana安装
```
官方参照 ：
https://www.elastic.co/downloads/kibana
```

1.下载
> 以下安装包最好用专门的下载工具下载，因为国内网络不是很稳定，经常会下载失败
```
wget https://download.elastic.co/kibana/kibana/kibana-4.5.1-linux-x64.tar.gz
```
2.解压
```
tar -zxvf  kibana-4.5.1-linux-x64.tar.gz 
```

3.运行
```
cd kibana-4.5.1-linux-x64 && bin/kibana

```

4.测试是否运行成功
```
浏览器输入 loclahost:5601
```
![img](https://github.com/yuexing0921/ELK/blob/master/img/init-runing-kibana.png)
出现上面的界面，说明kibana安装成功了