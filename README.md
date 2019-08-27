公司网络通过代理才能上网，git无法直接访问
设置了git http.proxy 也无法正常上网
从网络上找到了windows平台下配置的方法：
1.找到git用户的~目录：
2.进入.ssh目录
3.把config文件拷贝进.ssh目录
4.修改config文件中代理IP和Port参数