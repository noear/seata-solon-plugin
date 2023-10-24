# seata-solon-plugin


###  nami

nami, 是 solon rpc 的客户端。它有过滤器接口，可以用于传递 seata 的头信息

### solon

solon 有拦截器，用于控制 aop 控制。。。如果全局控制，可以用 RouterInterceptor

* 这个是 Web 请求过程的示意图：

https://solon.noear.org/article/242


* Solon 处理 AOP 主解的方式：

https://solon.noear.org/article/35