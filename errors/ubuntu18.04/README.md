## 在Ubuntu18.04中遇到的问题及解决方式

### 1. Ubuntu18.04 开机自启动脚本
[Ubuntu18.04 开机自启动脚本](https://blog.csdn.net/qq_36328643/article/details/89359724)
***
### 2. Ubuntu下解决端口被占用问题

为了解决端口占用问题，我们可以通过端口查找进程，再通过该进程的ＰＩＤ来杀掉该进程。
```bash
$ sudo lsof -i:端口号  
$ sudo kill PID号
```

### 3. Ubuntu下笔记本触碰板右键失灵
在terminal运行命令
```bash
$ gsettings set org.gnome.desktop.peripherals.touchpad click-method areas
```

### 4. Ubuntu 18.04启动太慢
[Ubuntu18.04启动太慢不能忍](https://www.cnblogs.com/gaowengang/p/10854042.html)