










# 工具
[linux下passwd命令设置修改用户密码](https://www.cnblogs.com/Alanf/p/7994324.html)<br>
[SSH客户端神器MobaXterm，该抛弃putty、Xshell和CRT了](https://baijiahao.baidu.com/s?id=1593541647064594276&wfr=spider&for=pc)<br>
[MobaXterm 官网](https://mobaxterm.mobatek.net/)<br>
[使用xrdp实现windows 远程桌面连接linux](https://blog.csdn.net/qq_33530388/article/details/64502902)<br>
另外修改一下：sudo vim /etc/xrdp/xrdp.ini <br>
[xrdp1] //用户名，密码，IP,端口都改成你自己的<br>
name=sesman-Xvnc<br>
lib=libvnc.so <br>
username=ask <br>
password=ask <br>
ip=127.0.0.1 <br>
port=-1 <br>
<br>
[xrdp3] //可以登陆的，所以 xrdp1的配置，模仿它<br>
name=vnc-any <br>
lib=libvnc.so <br>
ip=ask <br>
port=ask5900 <br>
username=na <br>
password=ask <br>

[Linux与Windows共享文件夹之samba的安装与使用（Ubuntu为例）](https://www.cnblogs.com/gzdaijie/p/5194033.html)<br>
