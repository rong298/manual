## nc 使用

```
文件夹拷贝：

1. 目标文件服务器：

nc -l 12345|tar xvf -

2. 源文件服务器：

tar cvf - sites_enabled |nc 192.168.3.161 12345
```

文档来源：https://github.com/hy0kl/profile/blob/master/note/nc-transfer-file.md
