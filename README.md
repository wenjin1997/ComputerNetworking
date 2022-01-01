- [第1章 网络基础知识](#第1章-网络基础知识)
  - [1.1 计算机网络出现的背景](#11-计算机网络出现的背景)
  - [1.2 计算机与网络发展的7个阶段](#12-计算机与网络发展的7个阶段)
  - [1.3 协议](#13-协议)
  - [1.4 协议由谁规定](#14-协议由谁规定)
  - [1.5 协议分层与OSI参考模型](#15-协议分层与osi参考模型)
# 第1章 网络基础知识
## 1.1 计算机网络出现的背景
计算机网络，根据其规模可分为WAN(Wide Area Network, 广域网)和LAN(Local Area Network, 局域网)等。
## 1.2 计算机与网络发展的7个阶段
批处理(Batch Processing)：是指事先将用户程序和数据装入卡带或磁带，并由计算机按照一定的顺序读取，是用户所要执行的这些程序和数据能够一并批量得到处理的方式。
分时系统(TSS)：是指多个终端与同一个计算机连接，允许多个用户同时使用一台计算机的系统。
**计算机使用模式的演变**
|年代|内容|
|----|----|
|20世纪50年代	|批处理时代|
|20世纪60年代	|分时系统时代|
|20世纪70年代	|计算机间通信时代|
|20世纪80年代	|计算机网络时代|
|20世纪90年代|互联网普及时代|
|2000年	|以互联网为中心的时代|
|2010年|无论何时何地一切以TCP/IP的网络时代|
## 1.3 协议
TCP/IP就是IP、TCP、HTTP等协议的集合。
简单来说，协议就是计算机与计算机之间通过网络实现通信时事先达成的一种“约定”。两台计算机之间必须能够支持相同的协议，并遵循相同协议进行处理，这样才能实现相互通信。
分组交换是将大数据分割为一个个叫做包(Packet)的较小单位进行传输的方法。
## 1.4 协议由谁规定
ISO制定了一个国际标准OSI。
本书说明的TCP/IP是由IETF所建议的、致力于推进其标准化作业的一种协议。
## 1.5 协议分层与OSI参考模型
OSI参考模型将通信协议中必要的功能分为7层。
在这一模型中，每个分层都接收由它下一层所提供的特定服务，并且负责为自己的上一层提供特定的服务。上下层之间进行交互时随哦遵循的约定叫做“接口”。同一层之间所遵循的约定叫做“协议”。
应用层、表示层、会话层、传输层、网络层、数据链路层、物理层。
