#### nginx

##### 1.nginx的使用场景

```
静态资源服务
反向代理服务
api服务

tps/qps/rps

https://www.cnblogs.com/wangmo/p/8074879.html
https://mp.weixin.qq.com/s?__biz=MzIwNTc4NTEwOQ==&mid=2247484337&idx=1&sn=1e895699a2e20f182f1187fed7453855&scene=21#wechat_redirect


https://mp.weixin.qq.com/s?__biz=MzIwNTc4NTEwOQ==&mid=2247484337&idx=1&sn=1e895699a2e20f182f1187fed7453855&scene=21#wechat_redirect

https://mp.weixin.qq.com/s?__biz=MzIwNTc4NTEwOQ==&mid=2247484930&idx=1&sn=a046a61d95da1ac41886e98348c9e640&scene=21#wechat_redirect

apache一个进程同一时间只能处理一个连接。并且一个连接对应一个进程。所以在处理成千上万的连接的时候apchce的性能会大大降低。


nginx的优点：
	1.高并发，高性能
	2.可扩展性
		主要体现在模块化设计
	3.高可靠性
		一般运行在企业的边缘
	4.热部署
		不停止的升级启动nginx
	5.bsd许可证
	
nginx的4个组成部分
	nginx的二进制可执行文件，又各个模块源码编译出的一个文件
	nginx.conf配置文件，控制nginx的行为
	access.log，记录每一条http的请求
	error.log,定位问题
	
```



