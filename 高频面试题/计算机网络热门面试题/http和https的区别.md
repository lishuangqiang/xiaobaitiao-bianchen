# http和https的区别

> 本文作者：[程序员小白条](https://github.com/luoye6)
>
> 本站地址：[https://xbt.xiaobaitiao.top](https://xbt.xiaobaitiao.top)

HTTP 传输的数据都是未加密的，也就是明文的，因此使用 HTTP 传输信息非常不安全。为了保证数据能加密传输，网景公司设计了 SSL(Secure Sockets Layer) 协议用于对 HTTP 传输的数据进行加密，从而就诞生了 HTTPS。二者主要区别如下：

1️⃣HTTPS 需要到 ca 申请证书，一般免费证书较少，因而需要一定费用。
2️⃣HTTP 信息是明文传输，HTTPS 则是具有安全性的 ssl 加密传输协议。
3️⃣HTTP 和 HTTPS 连接方式完全不同，端口也不一样，前者是 80，后者是 443。
4️⃣HTTP 的连接很简单，是无状态的。HTTPS 是由 SSL+HTTP 构建的可进行加密传输、身份认证的网络协议，比 HTTP 安全。