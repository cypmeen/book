# Okhttp3

## 引进原因

- 支持HTTP2.0/SPDY
- socket自动选择最好路线,并支持自动重连
- 拥有自动维护的socket连接池，减少握手次数
- 拥有队列线程池，轻松写并发
- 拥有Interceptors轻松处理请求与响应(比如GZIP压缩,LOG打印请求日志等)
- 实现基于Headers的缓存策略

