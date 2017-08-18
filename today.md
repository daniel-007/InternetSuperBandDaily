## 2017-08-01

> News
* [腾讯全民K歌坐拥4亿用户](https://news.cnblogs.com/n/576354/)
* [Apache宣布不再使用FB+PL License](http://news.51cto.com/art/201708/548345.htm)
* [已经2017年了，Android手机还需要root吗？](http://mobile.51cto.com/android-548378.htm)

> Github Repo
* [cc](https://github.com/ksarch-saas/cc) - 基于社区RedisCluster实现跨地域情况下的集群管理，可以实现自动failover，实现平台化运维，状态全部收敛于RedisCluster内部，proxy和controller组件全部是无状态，并实现在主从切换时同源增量同步，减小全量同步带来的网络带宽消耗和服务可用性下降，详细信息参加[Redis3.0设计架构](https://github.com/ksarch-saas/cc/blob/master/doc/tutorial_zh.md)。Star: 17. Lang: C.
* [redis](https://github.com/baidu/redis) -  百度出品的redis cluster controller，提供了redis http接口以及相关工具，用于控制redis cluster中每个node的相关状态。Star: 26. Lang: C.
* [r3proxy](https://github.com/ksarch-saas/r3proxy/) - 基于Twemproxy开发，支持Redis Cluster。增加集群拓扑发现功能，启动时proxy会从seed列表中随机选择一个server来获取集群状态，然后通过lua脚本解析集群信息并创建拓扑结构和slot信息，定时从RedisCluster通过cluster nodes extra命令来来获取集群信息，这组信息中包含了集群的主从关系和slot的分布，创建请求的路由信息。twemproxy自带failover： 配置文件server_failure_limit配置了后端连续失败几次后在一小段时间内剔除该节点。Star: 11. Lang: C.
* [qdb](https://github.com/reborndb/qdb) - 一个类似Redis的快速Key-Value数据库，可以将数据通过rocksdb等保存在磁盘来越过内存大小的限制并且将热点数据保存在内存中以提高性能。Star: 286. Lang: Golang.
* [GoRedis](https://github.com/latermoon/GoRedis) - 使用rocksdb作为存储层的RedisServer，数据不消耗内存，保持较高性能的情况下，同时获得海量存储特性,可以和官方redis互为主从，支持常用指令集，全部redis指令会转换为rocksdb操作。Star: 111. Lang: Golang.
* [goworld](https://github.com/xiaonanln/goworld) - 一款开源的分布式可扩展的游戏服务器引擎。Star: 208. Lang: Golang.
* [dissertation](https://github.com/ongardie/dissertation) - Raft研究与实践。Star: 172. Lang: Markdown.

> Blog
* [WebSocket通信协议应用安全问题分析](http://developer.51cto.com/art/201708/548391.htm) 
* [QEMU动态翻译器](https://mp.weixin.qq.com/s?__biz=MzAxOTAzMDEwMA==&mid=2652503606&idx=1&sn=d0b7fc64a42a760a5555526013cf87ef&chksm=8020170db7579e1b39049f27ed67fc4b30b8aa2e3e311ebe9be5001066b42a98f5d3a7bc87d0&mpshare=1&scene=1&srcid=0818hBSQKwMCwW3I027MygtF&pass_ticket=tsrnk41%2B1YaDrZahssKKs22LQoWEb2v1hYaleqiMq0dT2RT1xVJyCq1gUgAbGuZ8#rd) 
* [谍影重重：中国DDoS产业现状大揭秘](https://mp.weixin.qq.com/s?__biz=MjM5MzgxMTgwOA==&mid=2658254169&idx=1&sn=22b5217ed132a9e008e799931a8d40ea&chksm=bd1441568a63c840b279f17465cb4fdb4b156981e3a293b5e8d9d801e289f7bb8b8bac2bee91&mpshare=1&scene=1&srcid=08189heQDZZUJMM0jq86jmNw&pass_ticket=tsrnk41%2B1YaDrZahssKKs22LQoWEb2v1hYaleqiMq0dT2RT1xVJyCq1gUgAbGuZ8#rd) 

> Misc
* [雷军：想找人才一定要不惜血本，想留住他们呢？](https://mp.weixin.qq.com/s?__biz=MzA5NTI1MTgxOQ==&mid=2650902586&idx=1&sn=ddc8a9c5c8024ab0202068ab0321e0d6&chksm=8bb70c3ebcc085288ef1b4267b17f6f37280677d6066df733eb1108da512dc288e55edd8b4c9&mpshare=1&scene=1&srcid=0816OvtPiJsx3yx3mO1NmfzZ&pass_ticket=tsrnk41%2B1YaDrZahssKKs22LQoWEb2v1hYaleqiMq0dT2RT1xVJyCq1gUgAbGuZ8#rd) 
* [如何客观评价程序员的水平？](https://mp.weixin.qq.com/s?__biz=MzA3MjEyNTE4MQ==&mid=2652730801&idx=1&sn=8abff4947a5037ad77910f4f783a5246&chksm=84caca23b3bd433585f0f9229120d99492e9e682c2deb11609fd3c90c9df3733a49ba6fe7f8b&mpshare=1&scene=1&srcid=0816r0DpwWbi6gGXMrtAORdK&pass_ticket=tsrnk41%2B1YaDrZahssKKs22LQoWEb2v1hYaleqiMq0dT2RT1xVJyCq1gUgAbGuZ8#rd) 
* [一文读懂联通780亿混改方案：三大掘金路线曝光 将引爆混改行情](https://mp.weixin.qq.com/s?__biz=MjM5MjQzNTc4MA==&mid=2650713250&idx=1&sn=79941cbd567b770c8c450e62846da0ee&chksm=beac578989dbde9fb3ca24b52201f1584f88544fbb7f2c5148f6643ce5bb2f9400b7a695d98c&mpshare=1&scene=1&srcid=0818KBByLj6N3tKBX9cyHZNI&pass_ticket=tsrnk41%2B1YaDrZahssKKs22LQoWEb2v1hYaleqiMq0dT2RT1xVJyCq1gUgAbGuZ8#rd) 
* [印度乞丐与印度人](https://mp.weixin.qq.com/s?__biz=MTQzMTE0MjcyMQ==&mid=2666509532&idx=1&sn=2fdac367fc53c80a366d6ab2e73a37e5&chksm=666962f2511eebe4631f5c47970bdbc0fab58ce8875505b641dd7775b04bc539b22a2f9ec38b&mpshare=1&scene=1&srcid=0818u75v35liPpLJxf0b6Y4e&pass_ticket=tsrnk41%2B1YaDrZahssKKs22LQoWEb2v1hYaleqiMq0dT2RT1xVJyCq1gUgAbGuZ8#rd) 