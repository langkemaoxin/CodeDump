## Apollo源码分析





目标：给apollo增加 缓存的加密

https://github.com/apolloconfig/apollo.net/tree/v2.6.0





#### 1、什么是长连接？Http Long Polling，和平常所知道的TCP握一次手就结束有什么不同？





#### 2、定时拉取配置具体是怎么实现的？





#### 3、配置保存在内存中，保存在本地系统缓存，究竟是如何实现的？

这里是缓存文件的接口，默认实现的是 `LocalPlaintextCacheFileProvider` ，也就是明文的存储

![image-20220215094746076](F:\源码研究\CodeDump\CodeDump\Apollo源码分析.assets\image-20220215094746076.png)



#### 4、如何判定服务不可用？如何判定网络不通畅？

#### 5、订阅更新通知，具体如何实现？

#### 6、本地开发模式，究竟有什么不一样

