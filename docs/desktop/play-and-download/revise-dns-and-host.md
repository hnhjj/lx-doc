---
id: revise-dns-and-host
title: 修改DNS和HOST
---

**改完 DNS 或 HOST 后可能需要重启软件或电脑才会生效**

**Windows:**

DNS 修改方法(7~8 为可选操作):

1. <kbd>windows</kbd>+<kbd>e</kbd>打开资源管理器，在上方导航栏中输入控制面板然后回车（能打开控制面板就行）;

2. 将右上角查看方式修改为大图标，找到`网络和共享中心`;

3. 找到你正在使用的网络，点击连接后的蓝色字体`[一般为以太网 XXX 或者 WLAN(WIFI 名称)]`;

4. 弹出的窗口中，点击属性，双击`internet 协议版本4(TCP/IPv4)`;

5. 将`自动获得 DNS 地址`修改为`使用下面的DNS地址`;

6. 首选服务器填写`8.8.8.8`备用服务器填写`223.6.6.6 `。

7. <kbd>windows</kbd>+<kbd>r</kbd>输入 cmd 回车运行。

8. 输入`ipconfig /flushdns`回车运行。

HOST 修改方法:

1. 打开`C:\WINDOWS\system32\drivers\etc`;

2. 用记事本打开里面的`hosts`文件（无后缀）;

3. 在下面加上：

   ` 97.64.37.235 ts.tempmusic.tk`

   `97.64.37.235 tm.tempmusic.tk`

4. 保存

**MacOS:**

DNS 修改方法:

1. 俺母鸡啊，自行百度

HOST 修改方法:

1. 我不到啊，自行百度
