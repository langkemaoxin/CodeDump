## keepalived 

##### 什么是KeepAlived

Keepalived是基于vrrp协议的一款高可用软件。

keepalived有一台主服务器，和多台备服务器。每台机器上都部署同样的服务，然后对外提供一个虚拟IP，默认指向主服务器，当主服务发生故障时，虚拟IP地址就自动漂移到了备用服务器



##### 什么是vrrp协议

它是一种容错协议，通过把一组路由器连接起来，形成一个虚拟的整体路由器，作为一个整体对外提供服务。计算机使用此虚拟路由器计算下一跳的地址时，如果某一个处理此任务的路由器发生了错误，那么会自动的换到其他的设备继续提供服务。虚拟路由

<img src="D:\GIT\CodeDump\keepalived.assets\image-20220215212819427.png" alt="image-20220215212819427"  />



参考连接：https://www.cnblogs.com/dj0325/articles/9986109.html







