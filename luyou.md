https://unclebiglu.github.io/etc/nat/
## 一、IP 子网掩码 网关 DHCP PPPoE

IP
子网掩码
网关-路由器，连接外网和内网
DHCP：编码的人，维护秩序
PPPoE:点对点通信
参考文章
网络5大基础丨IP地址，子网掩码、网关、DHCP服务及PPPoE拨号 - 工业通信发烧友的文章 - 知乎
https://zhuanlan.zhihu.com/p/112862231

## 二、路由器工作原理
1、名词解释：
1）路由：从源主机到目标主机的对数据包选择路径的过程
2）路由器：路由器接收到一个IP数据包，会根据包中得目标IP地址，来进行选择路径并转发
3）路由表：路由器是十字路口，路由表是路标
直连路由条目，当把接口得IP配置完毕并开启，会自动形成直连路由条目
我并不知道用以太线连接机械臂后，它和我的电脑之间进行了什么交易
电脑路由拿到数据后需要将数据发给机械臂
匹配不上走默认路由
记录路由信息的表 route -n
该IP的网卡是什么
本地是否有目标IP

## 三、https://github.com/ros-controls/ros_controllers/blob/noetic-devel/joint_state_controller/src/joint_state_controller.cpp
https://www.guyuehome.com/33038
