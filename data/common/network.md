# TCP 建立连接 为什么是三次握手？

第一次：client -> server，你能收到我的消息吗？

第二次：client <- server，能收到，你能收到我的消息吗？

第三次：client -> server，我也能收到你的消息

信道不可靠，至少需要三次握手来确保信道是**"可用的"**，**确保双方能收能发**

# TCP 释放连接 为什么是四次挥手

前两次用来释放 client -> server 方向的连接

后两次用来释放 client <- server 方向的连接

# 介绍下 http 2.0 中的多路复用

# 从输入 URL 到页面加载完成，发生了什么？

1. DNS 查询
2. 建立 TCP 连接
3. ...