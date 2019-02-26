# 发布订阅模式 和 观察者模式 有什么关系？

发布订阅模式属于广义上的观察者模式，是其最常见的一种实现

发布订阅模式会比「典型的观察者模式」多一个「发布订阅中心」

**典型观察者模式**

```
+-----------+  Fire Event  +------------+
|           |------------->|            |
|  Subject  |              |  Observer  |
|           |<-------------|            |
+-----------+   Subscribe  +------------+
```

**发布订阅模式**

```
+-----------+               +---------------+  Fire Event  +------------+
|           | Publish Event |               |------------->|            |
| Publisher |-------------->| Event Channel |              | Subscriber |
|           |               |               |<-------------|            |
+-----------+               +---------------+   Subscribe  +------------+
```

> 参考 [https://www.zhihu.com/question/23486749](https://www.zhihu.com/question/23486749)

# 用代码实现发布订阅模式

emmm...todo