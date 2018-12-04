










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

[VIM 提升]

https://github.com/tczengming/myvim/
希望能给大家做一个参考。插件用bundle (也有人叫vundle)管理的，推荐大家使用bundle，插件安装升级很方便
只要一个vimrc
先安装bundle
git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle
然后可下载我的.vimrc替换你的.vimrc
git clone https://github.com/tczengming/myvim.git      
下载后用myvim/myvimrc替换你的.vimrc (可自行修改其内容)
然后在vim中执行
BundleInstall!    就可以自动地更新安装插件,不用再手动去网上一个个下最新包了。
 缷载插件  :BundleClean

