

<a id="批量合并md文件--type命令"></a>
## 批量合并MD文件--Type命令
把需要拼接的md文件放入一个文件夹内

打开命令界面:Windows+R 输入cmd
进入md文件所在位置:cd+文件夹路径

将拼接结果输出到指定路径的res.md文件内type *.md > 指定路径/res.md
【千万不要指定为想要合成的md文件所在文件夹，不然会出现无限合并，注意注意！！】

无需提前建立res.md空文件
md文件的拼接顺序需要手动调整

https://juejin.cn/post/7103422838572318757


<a id="debian系统升级的基本步骤"></a>
# Debian系统升级的基本步骤

检查系统版本信息：通过命令lsb_release -a查看当前系统版本。
更新软件包列表：使用命令apt-get update更新软件包列表。
升级所有已安装的软件包：使用命令apt-get upgrade。
进行系统升级：使用命令apt dist-upgrade进行系统升级。
更改APT源：如果默认源下载速度慢，可以更改到更快的镜像源，例如阿里云镜像源。
详细步骤和注意事项
检查系统版本信息：

使用命令lsb_release -a查看当前系统版本。
更新软件包列表：

使用命令apt-get update更新软件包列表，确保所有软件包都是最新的。
升级所有已安装的软件包：

使用命令apt-get upgrade升级所有已安装的软件包。
进行系统升级：

使用命令apt dist-upgrade进行系统升级，这可能会安装或升级多个包。
更改APT源：

如果默认源下载速度慢，可以更改到更快的镜像源。例如，使用阿里云的镜像源，可以按照以下步骤更改：
编辑文件/etc/apt/sources.list，将默认源替换为阿里云的镜像源地址。
保存文件后，使用命令apt-get update更新软件包列表。
备份重要数据：

在进行系统升级之前，建议备份重要数据，以防升级过程中出现问题导致数据丢失。
使用虚拟控制台：

为了在远程升级时获得额外的可靠性保障，建议使用screen程序生成的虚拟控制台执行升级过程，以确保即使远程连接暂时中断，升级过程也不会被打断。


<a id="2个路由器有线桥接好还是无线桥接好"></a>
# 2个路由器有线桥接好还是无线桥接好
悟途网2017年04月20日 22:44阅读(26563)字号(A-A+)
两个路由器有线桥接好还是无线桥接好？经常有用户咨询悟途网小编这个问题。实际上，有线桥接、无线桥接，这2种方式，各自有优点，也都有缺点。
悟途网小编觉得，只要你了解了它们各自的优缺点，在结合自己的需求，就可以选择适合自己的方式了。
一、有线桥接优缺点分析
2个路由器有线桥接好还是无线桥接好？
1、有线桥接优点
（1）、稳定性好
两个路由器用有线桥接的方式连接上网，最大的一个优点，就是有线桥接后，网络的稳定性、传输速度 不会受到影响。
（2）、距离更远
两个路由器有线桥接的另一个优点是，两个路由器之间的距离可以更远，理论上可以达到100米的距离，实际使用过程中，和网线质量有关系。
2、有线桥接缺点
（1）、不能实现无线漫游
两个路由器有线桥接，两个路由器的wifi名称不能相同，也就是不能实现无线漫游的。
关于无线漫游，可能很多新手用户理解不到。下面悟途网小编尽量用通俗易懂的语言，来简单的介绍下。
发生无线漫游有一个前提，那就是两个路由器的wifi信号覆盖范围重叠，或者交叉覆盖。
当手机连接路由器1的wifi信号，随着手机位置的变化，路由器1的wifi信号很差了；并且路由器2的wifi信号明显好于路由器1时，那么手机会自动切换到路由器2的wifi信号。
并且这个切换的过程是无缝的，也就是手机上网不会受到任何的影响。
实际上两个wifi信号之间的无线漫游，和手机信号的无线漫游类似的。当你去外地的时候，手机会自动接入当地的手机信号。
（2）、成本增加
两个路由器有线桥接时，需要用网线把两个路由器连接起来。如果两个路由器之间的距离有几十米远的话，那么需要额外增加几十上百元RMB的开支了。
（3）、实施困难
两个路由器有线桥接的时候，需要部署网线，如果网线有几十米长的话，那么部署网线比较麻烦，特别是穿过多个房间的时候。
当然了，如果之前你家里已经把网线部署好了，那就不存在这个问题了。
二、无线桥接的优缺点
2个路由器有线桥接好还是无线桥接好？
1、无线桥接优点
（1）、便于实施
两个路由器无线桥接，是通过无线的方式连接起来的。所以，两个路由器之间不需要用网线连接，不需要部署网线，方便部署实施。
（2）、可以实现无线漫游
两个路由器无线桥接后，可以实现无线漫游。
也就是无线桥接的时候，可以把两个路由器的wifi名称、wifi密码设置成相同的。手机连接wifi信号后，可以自动在两个路由器wifi信号之间切换。
2、无线桥接缺点
（1）、稳定性差
两个路由器无线桥接后，网络的稳定性、传输速度会受到影响。并且第二个路由器，距离第一个路由器越远，网络的稳定性、传输速度就越差。
（2）、距离受限
两个路由器无线桥接，由于是通过无线方式连接的。两个路由器之间的距离会受到限制，在室内一般10米左右的范围。
如果第二个路由器，距离第一个路由器太远了，将无法接收到第一个路由器的wifi信号，无法完成桥接。或者桥接后的网络稳定性、传输速度很差。


<a id="acer无线蓝牙鼠标重新配对方法："></a>
# Acer无线蓝牙鼠标重新配对方法：
原来需要同时长按鼠标左中右键三秒进入配对模式才可以。

左键-中键（最中间按钮）-右键 三键齐按 

参考资料
https://baijiahao.baidu.com/s?id=1684251219977233006&wfr=spider&for=pc


<a id="软件acrobatdcpro安装序列号"></a>
# 软件AcrobatDCPro安装序列号
1118-1583-7979-9484-4887-4319


<a id="catalina文件共享功能无法开启解决方案"></a>
# catalina文件共享功能无法开启解决方案
1、关闭设置面板（如果打开）

2、sudo launchctl load -w /System/Library/LaunchDaemons/com.apple.AppleFileServer.plist

3、sudo launchctl load -w /System/Library/LaunchDaemons/com.apple.smbd.plist

其他：
关闭共享偏好设置后，试试运行下面的命令，运行成功后再打开共享偏好设置
sudo /usr/libexec/configureLocalKDC

参考链接
https://discussionschinese.apple.com/thread/254303066?sortBy=best


<a id="clashx需要使用管理员权限安装更新一个帮助程序"></a>
# clashx需要使用管理员权限安装更新一个帮助程序

解决办法1：

打开mac电脑的Terminal终端，在终端中执行如下系统管理员命令：

sudo launchctl enable system/com.west2online.ClashX.ProxyConfigHelper


<a id="clash急救节点"></a>
# clash急救节点
https://v2rayclashx.github.io/free-nodes/2024-10-12-free-v2ray.htm


https://clashnode.cc/free-node/2024-10-13-free-subscribe-node.htm

https://clash-meta.github.io/free-nodes/2024-10-13-clash-meta-node-github.htm

链接转化
https://acl4ssr-sub.github.io


<a id="mac快捷键cmmand按下去可以显示状态栏"></a>
# Mac快捷键cmmand+/按下去可以显示状态栏


<a id="debian永久修改dns"></a>
# Debian永久修改dns

echo "supersede domain-name-servers 1.1.1.1,8.8.8.8;" >> /etc/dhcp/dhclient.conf

链接: https://cakepanit.com/forward/d4ac701.html

supersede domain-name-servers 1.1.1.1,8.8.8.8;

debian的 /etc/resolv.conf配置文件中 也提示我们不要直接修改这个文件。
debiandns
它是一个软链接，指向 /run/resolvconf 目录下的“真实文件”。该文件是在系统启动时生成的；同时也是注释告诉我们不要直接修改该文件的原因。

经过了解，在网卡启动或机器启动时。系统中的dhclient程序即dhcp客户端。会向厂商的虚拟交换机发送dhcp请求获得网卡的 ip 网关 dns 等信息，并覆盖/etc/resolvconf/run/resolv.conf 文件。

echo "supersede domain-name-servers 172.22.xxx.xxx,10.66.xxx.xxx,10.68.xxx.xxx;" >> /etc/dhcp/dhclient.conf
echo 'supersede domain-name "xxx.bilibili.xxx";' >> /etc/dhcp/dhclient.conf

debian怎么清理空间
在Debian系统中清理空间通常可以通过以下方法进行：

清理缓存文件：

sudo apt-get clean
这个命令会删除所有已下载的包的.deb文件。

清理不需要的依赖：

sudo apt-get autoremove
这个命令会删除已安装包的依赖，如果这些依赖不被其他安装的包使用，则会被删除。

清理旧内核和不再需要的依赖：

sudo apt-get autoclean
这个命令会删除已经删除的包的.deb文件以及他们的依赖。

清理用户缓存（对于Mozilla Firefox等）：

rm -rf ~/.cache/*
清理用户日志文件：

rm ~/.local/share/gnome-logs/*
清理不需要的语言支持包：

sudo apt-get purge language-pack-*
清理不需要的字体：

sudo apt-get purge fonts-*
确保在执行这些清理操作之前，你已经备份了重要的数据和配置。使用df -h命令可以查看磁盘空间使用情况，确保有足够的空间进行清理操作。


<a id="在服务器上安装dockerdocker-compose"></a>
# 在服务器上安装docker/docker-compose

https://tech.yemengstar.com/docker-install-docker-docker-compose-server/


<a id="excel表示距离现在小于等于x天"></a>
# Excel表示距离现在小于等于X天
=DATEDIF(A1,TODAY(),"d")<1

<a id="flatnotes部署教程"></a>
# flatnotes部署教程
https://developer.aliyun.com/article/1512826

三、本地环境检查
3.1 检查Docker服务状态
检查Docker服务是否正常运行，确保Docker正常运行。
[root@jeven ~]# systemctl status docker
● docker.service - Docker Application Container Engine
   Loaded: loaded (/usr/lib/systemd/system/docker.service; enabled; vendor preset: disabled)
   Active: active (running) since Wed 2023-08-23 23:41:16 CST; 1 weeks 1 days ago
     Docs: https://docs.docker.com
 Main PID: 9562 (dockerd)
    Tasks: 50
   Memory: 1.4G
   CGroup: /system.slice/docker.service
3.2 检查Docker版本
检查Docker版本
[root@jeven ~]# docker version
Client: Docker Engine - Community
 Version:           20.10.17
 API version:       1.41
 Go version:        go1.17.11
 Git commit:        100c701
 Built:             Mon Jun  6 23:05:12 2022
 OS/Arch:           linux/amd64
 Context:           default
 Experimental:      true

Server: Docker Engine - Community
 Engine:
  Version:          20.10.17
  API version:      1.41 (minimum version 1.12)
  Go version:       go1.17.11
  Git commit:       a89b842
  Built:            Mon Jun  6 23:03:33 2022
  OS/Arch:          linux/amd64
  Experimental:     false
 containerd:
  Version:          1.6.6
  GitCommit:        10c12954828e7c7c9b6e0ea9b0c02b01407d3ae1
 runc:
  Version:          1.1.2
  GitCommit:        v1.1.2-0-ga916309
 docker-init:
  Version:          0.19.0
  GitCommit:        de40ad0
3.3 检查docker compose 版本
检查Docker compose版本，确保2.0以上版本。
[[root@jeven ~]# docker compose version
Docker Compose version v2.19.1
四、下载flatnotes镜像
从docker hub下载flatnotes镜像
[root@jeven ~]# docker pull  dullage/flatnotes
Using default tag: latest
latest: Pulling from dullage/flatnotes
1d5252f66ea9: Pull complete
eefb43356e06: Pull complete
c26db0eb1f01: Pull complete
300843d99304: Pull complete
daddf7df59b6: Pull complete
fd5b7d323a9e: Pull complete
956d12ab1aba: Pull complete
3a27da5a148e: Pull complete
9bc9c825c797: Pull complete
4f4fb700ef54: Pull complete
2dff9aeca767: Pull complete
745990a309e1: Pull complete
cf33157fe535: Pull complete
1f4f074b255f: Pull complete
042bd107273a: Pull complete
Digest: sha256:666b237abff5a16d781ee7f06ccdadef9e42951de3ec320a071407a9e85666ef
Status: Downloaded newer image for dullage/flatnotes:latest
docker.io/dullage/flatnotes:latest
五、部署flatnotes笔记工具
5.1 创建目录
新建挂载目录
mkdir -p /data/flatnotes/data   && cd /data/flatnotes/
目录授权工作
 chmod -R 777 /data/flatnotes/
5.2 使用docker-cli部署
使用docker-cli命令部署flatnotes笔记工具
生成随机KEY
[root@jeven flatnotes]# cat /dev/urandom | tr -dc 'a-zA-Z0-9' | fold -w 24 | head -n 1
Nl1rQmfg4gsnJfBfsmkXOo7G
docker run -d \
   --restart unless-stopped \
   --name flatnotes \
   -p "28880:8080" \
   -v "/data/flatnotes/data:/data" \
   -e "FLATNOTES_AUTH_TYPE=password" \
   -e "FLATNOTES_USERNAME=admin" \
   -e "FLATNOTES_PASSWORD=admin" \
   -e "FLATNOTES_SECRET_KEY=Nl1rQmfg4gsnJfBfsmkXOo7G" \
   -e "PORT=8080" \
  dullage/flatnotes:latest
5.3 编辑docker-compose.yaml文件
编辑docker-compose.yaml文件，内容如下：
version: '3'

services:
  flatnotes:
    image: dullage/flatnotes:latest
    container_name: flatnotes
    restart: always
    ports:
      - 28880:8080
    volumes:
      - /data/flatnotes/data:/data
    environment:
      - FLATNOTES_AUTH_TYPE=password
      - FLATNOTES_USERNAME=admin
      - FLATNOTES_PASSWORD=admin
      - FLATNOTES_SECRET_KEY=Nl1rQmfg4gsnJfBfsmkXOo7G
      - PORT=8080
5.4 创建flatnotes容器
使用docker compose快速创建flatnotes容器

[root@jeven flatnotes]# docker compose up -d
[+] Running 2/2
 ⠿ Network flatnotes_default  Created                                                                                                                                     0.1s
 ⠿ Container flatnotes        Started                                                                                                                                     0.4s
5.5 检查flatnotes容器状态
检查容器状态，确保flatnotes容器正常启动。
[root@jeven flatnotes]# docker ps
CONTAINER ID   IMAGE                      COMMAND            CREATED          STATUS          PORTS                                         NAMES
23eebd85b174   dullage/flatnotes:latest   "/entrypoint.sh"   13 seconds ago   Up 13 seconds   0.0.0.0:28880->8080/tcp, :::28880->8080/tcp   flatnotes
5.6 检查flatnotes容器日志
检查flatnotes容器日志，确保服务正常运行。
[root@jeven flatnotes]# docker logs flatnotes
Setting up user and group...
Adding group `flatnotes' (GID 1000) ...
Done.
Adding user `flatnotes' ...
Adding new user `flatnotes' (1000) with group `flatnotes' ...
Creating home directory `/home/flatnotes' ...
Copying files from `/etc/skel' ...
Setting file permissions...
WARNING: Breaking changes introduced in version 3.x:
  - The port flatnotes uses inside the Docker container has been changed to 8080 (previously 80).
  - To accompany the above change, support for the PORT environment variable has been removed.
  - The note directory inside the Docker container has moved from /app/data to simply /data.
Starting flatnotes...
2023-09-01 10:22:51 [INFO]: Creating new index
INFO:     Started server process [1]
INFO:     Waiting for application startup.
INFO:     Application startup complete.
INFO:     Uvicorn running on http://0.0.0.0:8080 (Press CTRL+C to quit)

<a id="githubfork233boy脚本安装命令fork仓库"></a>
# GitHubfork233boy脚本安装命令fork仓库

wget https://github.com/417mls/sing-box/archive/main.tar.gz -O sing-box-main.tar.gz;tar -zxvf sing-box-main.tar.gz;cd sing-box-main;chmod +x i*;./i* -l


<a id="iphone登录nextcloud-nexnsurl-error-domain错误999"></a>
# iphone登录Nextcloud-nexnsurl-error-domain错误999
看了一下。解决办法，在Nextcloud配置文件config.php 中添加以下行解决了这个问题：
'overwriteprotocol' => 'https',
登录一切正常。登录后在把这行代码注释掉，也没有问题。

https://www.xiaoyaoxi.com/forums/topic/1040


<a id="linuxdhcp模式下手动设置dns"></a>
# LinuxDHCP模式下手动设置DNS

之前的文章中提到我们可以通过更改 DNS 的方式来解锁 Netflix 等流媒体，但如果你的 Linux vps 使用的是 DHCP 自动获取网络参数的话，编辑 /etc/resolv.conf 其实是无效的。每次网络重启后，DHCP 客户端服务都会自动恢复 DNS 设置为网关所下发的 ip。此时我们需要稍微修改 DHCP 客户端服务的配置文件才可以，具体方法如下。
使用任意编辑器如 vim 或 nano 打开 /etc/dhcp/dhclient.conf ，并在任意位置添加一行：
supersede domain-name-servers 8.8.8.8;
保存后重启网络接口即可。其中 8.8.8.8 可改为你所需要的 DNS 服务器 ip。
此时再打开 /etc/resolv.conf 可以发现，该文件已经自动添加上了刚刚所设置的 DNS。
除此之外，也可以编辑 /etc/network/interfaces 文件，切换为为手动配置 ip 地址，再编辑 /etc/resolv.conf 同样能够达到自定义 DNS 的目的。
示例文件如下：
auto eth0
iface eth0 inet static
address 192.168.0.100
gateway 192.168.0.1
netmask 255.255.255.0


<a id="macoscatalina删除预装应用"></a>
# MacOSCatalina删除预装应用
关机
开机-听到开机声音后按住com+r 进入恢复模式
选择工具（utilities）-> 终端（terminal）
输入csrutil disable关机系统保护
想要打开系统保护时重复以上步骤，终端输入命令为csrutil enable
然后重新启动使其自然进入系统

终端执行：
sudo -i 
然后执行：
sudo mount -uw /
删除命令 ：
sudo rm -rf 
删除实例：删除苹果TV （可以进入访达-应用程序 拖入终端）
sudo rm -rf /System/Applications/TV.app


<a id="macoscatalina关闭开机声音"></a>
# macOSCatalina关闭开机声音

关闭
sudo nvram StartupMute=%01
开启
sudo nvram StartupMute=%00


<a id="mac三指拖移选中文字功能"></a>
# Mac三指拖移选中文字功能
辅助功能-指针控制-触摸板选项-启用拖移-三指拖移

页面文字多，需滚动选中的用shift键盘辅助

也可以用三指 向下滑动选中

使用三个手指在触控板上滑动，窗口可以跟随手指移动，文字在三指滑动过程中自动选中。


<a id="mac上给iphone照片备份重命名修改原数据日期等流程"></a>
# Mac上给iPhone照片备份重命名修改原数据日期等流程
1、用手机隔空投送到电脑上
2、用renamer软件重命名，流程如下
     （1）photos-insert day taken-add date &time-file created
    （2） number-name only-00001-
      重命名成2020-10-12 01867格式
3、用image exif editor软件统一修改日期（image create date）
4、用metaimage软件进行校验日期（原数据-date三项）
5、检验完毕，备份入库


<a id="mac刷新dns"></a>
# Mac刷新dns
sudo killall -HUP mDNSResponder

查看当前dns
scutil --dns


<a id="mac和windows局域网文件共享设置方法"></a>
# Mac和Windows局域网文件共享设置方法

一、Windows访问Mac：
主要方法链接：

https://blog.csdn.net/wjavadog/article/details/92214107

重点1：打开mac共享设置里的  文件共享和 远程登陆（应该不需要）
重点2：点按“WINS”标签，然后输入 Windows 电脑使用的工作组名称。
（查看Windows系统信息中工作组的名字）
wins服务器写mac电脑局域网ip地址（如：192.168.0.1）

所有设置完毕
打开 windows 机器，win+r 输入你 mac 的地址（如：\\TAIRAN-MAC），回车输入用户名密码(MAC的)就可以访问啦。

方法之二参考：
https://post.smzdm.com/p/adwrez3k/

其他参考资料：
家庭版 共享功能 阉割 可参考以下方法：
https://blog.csdn.net/DovSnier/article/details/103476679

https://www.pianshen.com/article/3446560809/

其他问题：
WINDOWS功能-smb相关项目打开
WiFi网络设置为 专用网络-高级共享设置-文件共享/网络发现

二、Mac访问Windows
1、Windows打开网络发现和文件共享功能
2、Mac打开文件共享功能
3、连接局域网中的window电脑输入window用户名和密码连接

提示：可在Windows电脑上新建新的共享文件夹 在文件夹属性设置（高级共享）


<a id="mac安全选项开启任何来源"></a>
# mac安全选项开启任何来源
sudo spctl --master-disable


<a id="mac开机自动显示隐藏文件解决办法"></a>
# Mac开机自动显示隐藏文件解决办法
终端输入：defaults write com.apple.finder AppleShowAllFiles -bool false 然后点回车键
当然你也可以默认显示隐藏文件只需要终端输入：defaults write com.apple.finder AppleShowAllFiles -bool true每次开机都会默认显示隐藏文件


<a id="mac弹出”无法执行，因为您没有正确的访问权限“"></a>
# mac弹出”无法执行，因为您没有正确的访问权限“

macOS 运行xxxx.command文件时，弹出”无法执行，因为您没有正确的访问权限“窗口，如果解决这个问题呢？

方法一：

打开终端工具，输入以下命令：

sudo sh注意后面有空格

然后再把.command 文件直接拖入终端按回车键即可正常运行。

方法二:

打开终端工具，输入以下命令：

bash注意后面有空格

把.command 文件直接拖入终端按回车键即可正常运行。

方法三:

打开终端工具，输入以下命令：

sudo chmod -R 777注意后面有空格

把.command 文件直接拖入终端按回车键，最后双击.command文件即可正常运行。

https://www.bilibili.com/read/cv22885859/ 


<a id="mac无法连接蓝牙鼠标解决方案"></a>
# Mac无法连接蓝牙鼠标解决方案
解决方法：
　　1、关闭wifi；
　　2、连接蓝牙键盘；
　　3、稍等一会，再连接wifi就可以了。
另外，苹果客服给出的解决方案如下（没有亲测，不知效果）
　　PRAM 重置
关机，拔掉所有外设，接上电源。
启动时同时按住 Command, Option, p, r ， 听到三次 dang 的开机声音后放开。
启动电脑
　　SMC 重置
关机，拔掉所有外设，接上电源。
同时按住 Shift, Control, Option, 电源键 ，此时电脑没有任何反应，等待十秒放开。
继续等待十秒，启动电脑。
　　根据苹果客服，电脑出现其他奇葩情况时候也可以使用这个办法解决。

https://www.cnblogs.com/liuzhixian666/p/13568926.html


<a id="mac网络恢复重装系统-2100f故障处理办法（可以一试）"></a>
# Mac网络恢复重装系统-2100F故障处理办法（可以一试）
关掉 我的查找 
退出 iCloud
再重新shift option command R 重装系统


<a id="mac自带烧录u盘方法"></a>
# Mac自带烧录u盘方法

找到关键词 External 对应 dev/disk3 ，则disk3即为U盘的磁盘编号。

再使用下方命令将U盘“卸载“（unmount）：

diskutil unmountDisk /dev/disk2

接下来就是用dd命令将ISO烧写到U盘上：

sudo dd if=/Users/ms/Desktop/ubuntu-22.04.4-desktop-amd64.iso of=/dev/rdisk2 bs=1m

注意 if后面是iso具体的路径，可以在Finder中手动拖动iso文件到窗口，将会自动生成路径地址。
of后面接的是U盘的磁盘编号（需要将disk3，换成rdisk3）


<a id="mac重置启动台"></a>
# mac重置启动台
defaults write com.apple.dock ResetLaunchPad -bool true
killall Dock


<a id="memos-部署教程"></a>
# Memos 部署教程
https://sspai.com/post/76247


<a id="memos自定义css相关链接"></a>
# memos自定义CSS相关链接
https://xulinfeng.xyz/posts/memos-custom-code/
https://blog.memos.ee/archives/190.html
https://ysicing.me/tools/memos-diy-style/

<a id="memos"></a>
#memos


<a id="nextcloudnotes服务器地址"></a>
# nextcloudnotes服务器地址
https://c.maluanshan.top/index.php


<a id="nextcloud上传限制方案"></a>
# nextcloud上传限制方案
Nginx 问题
* 事实上 413 错误是 Nginx 的上传文件大小限制导致的
*      
* 因此我们需要调整的是 Nginx


<a id="nextcloud官方推荐使用php74或更高版本以确保最佳性能和兼容性"></a>
# Nextcloud官方推荐使用PHP7.4或更高版本以确保最佳性能和兼容性
特别是，Nextcloud 27.0.0版本开始，官方警告需要升级到PHP 8.1。
Nextcloud打开缓慢\卡顿的一些优化
https://blog.csdn.net/abilix_tony/article/details/141098086

https://itlanyan.com/optimize-nextcloud/

https://blog.csdn.net/i12344/article/details/107712473


<a id="wwwserverpanelvhostnginx修改反向代理删除无用代理否则无法建立网站"></a>
# /www/server/panel/vhost/nginx修改反向代理删除无用代理否则无法建立网站

<a id="ping-ip-网站"></a>
# Ping ip 网站
ping.pe

<a id="ps裁剪方法"></a>
# Ps裁剪方法
居中裁剪按住 alt+shift
正方形裁剪 按住 shift


<a id="reality自建教程"></a>
# Reality自建教程
参考网站：https://lainbo.dev/custom-reality?locale=zh
https://www.smallstep.one/article/reality-domain


<a id="resilio-sync一些知识"></a>
# resilio sync一些知识

https://www.zhihu.com/question/60919926?utm_id=0

http://blog.vimge.com/archives/other/say-bye-resilio-sync.html

<a id="shadowrocket小火箭ios账号下载"></a>
# shadowrocket小火箭ios账号下载

idshare.me_jgesw156@icloud.com

t!43ze6D

https://idshare001.me/goso.html

<a id="v2rayn在绕过大陆下参数设置"></a>
# V2rayN在绕过大陆下参数设置

https://www.youtube.com/watch?v=fqREM6b25SY


<a id="v2rayu默认pac模式下打不开网站"></a>
# v2rayu默认pac模式下打不开网站

这个问题我也是找了很久才发现原因，偏好设置--General----取消勾选 “自动检测版本更新” 和 “启动或唤醒时自动从订阅中更新” 两个 选项，就OK了

pac 设置 -> 保存设置 建议GFW 列表更新

https://github.com/yanue/V2rayU/issues/1413

<a id="windows-1011删除左侧导航栏位置wps网盘、百度网盘等无用快捷方式"></a>
# Windows 10/11删除左侧导航栏位置WPS网盘、百度网盘等无用快捷方式
win11如何删除文件夹左侧的网盘-CSDN博客
之前我们在《删除 Windows 设备和驱动器中的 WPS网盘、百度网盘等快捷图标》文章中有介绍到如何快速删除Windows 10/11 “此电脑”下“设备和驱动器”部分出现诸如WPS软件、百度云盘、爱奇艺等对应的软件图标，有读者反馈说在左侧导航栏还有此类快捷方式，关键还没有鼠标右键“从**取消固定”或删除按钮，今日为大家简单补充如何删除左侧导航栏里顽固的快捷方式的过程，当然我们也可以通过该方式删除有关OneDrive等快捷方式。
删除步骤：
1、Win+R 打开运行栏/也可以直接Win键打开Windows开始菜单栏，输入 regedit 并按回车键，打开注册表编辑器。
2、在注册表编辑器中，按照以下路径展开注册表：
HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace
3、在“NameSpace”下，依次展开文件夹子目录，找到需要删除的快捷方式目录，直接右键点击对应的文件夹目录，并选择“删除”即可。删除后，刷新“此电脑”页面或重新打开该页面，快捷方式图标已删除成功。

<a id="windows7精简版最终版下载"></a>
# Windows7精简版最终版下载
Windows7 SP1 7601.24540 by Lopatkin
magnet:?xt=urn:btih:31AAA22E5E00C2BDBB4BC742F6DF3DF322763BEE

<a id="windows10精简版-最终版"></a>
# Windows10精简版 最终版
https://www.423down.com/win10/page/4
https://blog.csdn.net/ganggang4321/article/details/108385821
https://www.423down.com/win10/page/4

<a id="windows上html文件批量转换成txt方法"></a>
# windows上html文件批量转换成txt方法

适用简书批量下载转换导入

HTML转换成TXT
参考连接：https://zhidao.baidu.com/question/879455751550513252.html
https://pan.baidu.com/s/1JrdQlHDUY7pbijt3V2oXbQ
链接: https://pan.baidu.com/s/1xIPX6HK7z5aeS-Eb1vUSXw 提取码: 9k71

相关资料已转存到自己的 百度网盘

其他工具：我的ABC软件工具箱

<a id="windows系统下制作windows-10系统u盘启动及安装指导"></a>
# Windows系统下制作Windows 10系统U盘启动及安装指导

安装教程如下
https://blog.csdn.net/qq_37592750/article/details/139784377

选用fat32格式

<a id="z-library私人域名"></a>
# Z-library私人域名
https://zlibrary-510.pm


<a id="两个路由器无线桥接的上网设置方法"></a>
# 两个路由器无线桥接的上网设置方法
链接：http://www.it528.com/skill/3490.html
两个路由器无线桥接设置方法。无线桥接这个功能，是一个比较实用的功能，一般在以下场景下会使用到：
已经有一个无线路由器了，但是该路由器的无线信号不能满足使用需求，家里部分区域没有wifi信号或者信号不好。
这个时候可以再买一个无线路由器回来，把两个路由器之间设置无线桥接，桥接成功后第二个路由器也可以上网了，从而实现增强无线信号的目的。

重要说明：
（1）、不同的无线路由器，无线桥接的设置方法会有一些差异，但是本质上都是相同的。在本文中，悟途网小编将用两个最新版的TP-Link路由器为例，来演示无线桥接设置方法。
（2）、在设置无线桥接的时候，通常我们把原来连接宽带上网的那一个路由器叫做：主路由器；把第二个路由器叫做：副路由器。
（3）、请确保你的主路由器是可以正常上网，如果主路由器无法上网，那么无线桥接后，副路由器也是不能上网的。
第一步、确定主路由器无线参数
在副路由器中配置无线桥接功能之前，你一定要知道主路由器的：无线名称、无线密码。因为在副路由器中设置无线桥接的时候，需要用到这些信息。
如有不清楚的，请自行登录到主路由器的设置页面，查看你的主路由器的无线名称和密码，如下图所示。
第二步、电脑连接副路由器
先把副路由器接通电源，然后电脑用网线连接到副路由器的LAN接口(1\2\3\4)。
注意问题：
（1）、主路由器和副路由器之间，不需要用网线来连接的。
（2）、如果是笔记本电脑，可以让笔记本电脑搜索、连接副路由器的无线信号；而不必用网线来连接笔记本电脑和副路由器了。
第三步、副路由器中设置桥接
温馨提示：
再次提醒大家，不同的无线路由器，无线桥接的设置有一些差异。在一篇文章中，悟途网小编没有办法把所有路由器的桥接设置方法都进行介绍。
所以，下面悟途网小编将使用目前用得最多的tplink路由器为例，来演示无线桥接的设置方法。其它品牌的无线路由器，也是可以参考设置的。
1、登录到设置页面
在电脑浏览器中输入 tplogin.cn 打开登录页面——>输入“管理员密码”，登录到副路由器的设置页面。

注意问题：
tplogin.cn是新版tplink路由器的设置网址；大家在设置的时候，请输入你路由器的设置网址来登录哦。
2、启用无线桥接功能
点击“应用管理”选项打开

然后点击“无线桥接”选项打开，如下图所示

3、运行无线桥接向导
点击“开始设置”按钮，进入无线桥接的设置向导页面

4、自动扫描信号
新版tplink路由器，此时会自动扫描附近的无线信号，如下图所示，稍微等待一会即可

5、连接主路由器信号
在无线信号扫描结果中，找到并选择 主路由器 的无线信号——>然后输入主路由器无线密码，如下图所示。

注意问题：
如果扫描结果中，没有被桥接的无线信号；可以尝试减小2个路由器之间的距离，或者手动扫描下信号。
6、修改副路由IP地址
新版tplink路由器，在设置无线桥接的时候，会自动从主路由器获取一个IP地址，如下图所示。请记录下来，以后需要用这个IP地址，来管理路由器。

重要说明：
如果你的副路由器没有这个功能，那么你需要在副路由器中，找到“LAN口设置”选项，手动修改副路由器的IP地址，修改的原则如下：
主路由器的LAN口IP地址是：192.168.1.1，则副路由器的LAN口IP地址修改为：192.168.1.X(2<X<254)这个范围中的IP地址，都是可以的。悟途网小编建议大家直接修改成：192.168.1.2
主路由器的LAN口IP地址是：192.168.0.1，则副路由器的LAN口IP地址修改为：192.168.0.X(2<X<254)这个范围中的IP地址，都是可以的。悟途网小编建议大家直接修改成：192.168.0.2
主路由器的LAN口IP地址是：192.168.2.1，则副路由器的LAN口IP地址修改为：192.168.2.X(2<X<254)这个范围中的IP地址，都是可以的。悟途网小编建议大家直接修改成：192.168.2.2

7、设置副路由器无线参数
建议大家把副路由器的 无线名称、无线密码 ，设置成与主路由器的 无线名称和密码相同。

8、关闭副路由器DHCP服务器
新版tplink路由器，在设置无线桥接后，会自动关闭DHCP服务器。所以，这里无需我们手动去关闭了。
如果你的路由器不具备自动关闭DHCP服务器的功能，则需要你在副路由器的设置页面中，找到“DHCP服务器”选项，手动进行关闭，如下图所示。

第四步、检查无线桥接设置是否成功
1、在浏览器中，输入副路由器新的IP地址，重新登录到副路由器的设置页面。

注意问题：
设置无线桥接后，副路由器将不能用原来的设置网址登录了，需要使用修改后的IP地址，才能登录到设置页面。
2、点击“应用管理”——>“无线桥接”——>可以看到“桥接状态为”，如果显示：桥接成功，说明两个TP-Link无线路由器桥接设置成功。

第五步、调整副路由器位置
如果副路由器所在的位置，距离主路由器太近了，将无法起到增强wifi信号的目的。
但是，如果副路由器距离主路由器太远，那么无线桥接后副路由器网络稳定性很差。
一般悟途网小编是建议大家，把副路由器摆放在，主路由器和原来无线信号较差区域的中间位置，而不要直接放在原来信号差的位置。
补充说明：
两个路由器无线桥接设置其实非常的简单，只要知道主路由器的无线名称、无线密码。那么登录到副路由器的设置页面，找到“无线桥接”设置选项，按照提示就可以完成设置。
但是，有2个地方大家一定要注意：
1、副路由器的IP地址问题
副路由器的IP地址，一定要修改成与主路由器的IP地址，在同一个网段，否则无线桥接设置完成后，将无法打开副路由器的设置页面。
目前很多品牌的无线路由器，在设置无线桥接的时候，都具备自动修改IP地址的功能，或者会提示用户修改IP地址。
如果你的路由器没有自己修改IP地址，也没有提示你修改。那么你需要找到“LAN口设置”选项，手动修改副路由器的IP地址。修改的原则，悟途网小编在3.6步骤中已经详细介绍过了。
2、副路由器DHCP一定要关闭
两个路由器设置无线桥接的时候，副路由器中的 DHCP服务器 功能一定要关闭掉；否则设置无线桥接后，网络会出现很多问题。
目前很多路由器在设置无线桥接的时候，会自动关闭掉自己的DHCP服务器功能，无需手动关闭了。
如果你不知道你的副路由器是否自动关闭了 DHCP服务器 ，建议在副路由器中，找到 DHCP服务器 选项，手动关闭掉。


<a id="体育锻炼"></a>
# 体育锻炼

周一：俯卧撑30x8  
周三：深蹲60x8
周五：跑步

<a id="使用命令行删除回收站中的所有文件"></a>
# 使用命令行删除回收站中的所有文件  
rm -rf ~/.local/share/Trash/*

<a id="入坑docsify一款神奇的文档生成利器"></a>
# 入坑docsify一款神奇的文档生成利器
https://baijiahao.baidu.com/s?id=1683928475208184783&wfr=spider&for=pc

https://blog.csdn.net/2401_86402635/article/details/141906177


<a id="全部还款日-11月"></a>
# 全部还款日-11月

| 日期| 项目001|项目002| 项目003|
| ----------- | ----------- | ----------- | ------ |
| 1|             |               |              |
| 2|             |               |              |
| 3|             |               |              |
| 4|             |               |              |
| 5|             |               |              |
| 6|             |               |              |
| 7|             |               |              |
| 8|             |               |              |
| 9|             |               |              |
| 10|             |               |              |
| 11|             |               |              |
| 12|             |               |              |
| 13|             |               |              |
| 14|             |               |              |
| 15|             |               |              |
| 16|             |               |              |
| 17|             |               |              |
| 18|             |               |              |
| 19|             |               |              |
| 20|             |               |              |
| 21|             |               |              |
| 22|             |               |              |
| 23|             |               |              |
| 24|             |               |              |
| 25|             |               |              |
| 26|             |               |              |
| 27|             |               |              |
| 28|             |               |              |
| 29|             |               |              |
| 30|             |               |              |
| 31|             |               |              |

<a id="券商佣金组成"></a>
# 券商佣金组成

链接：https://www.zhihu.com/question/619857110/answer/3189688424

先了解一下目前手续费的收费明细，2023年8月27日证监会下调印花税以后，
A股股票交易费用分四个部分：印花税、规费、过户费、券商交易佣金
印花税：成交金额的万5，向卖方单边征收，支付给财税部门的税收。上海股票及深圳股票均按实际成交金额的千分之一支付，此税收由券商代扣后由交易所统一代缴，债券与基金交易均免交此项税收。国家收取没有商量。点评：由原来的千1减半，现在只收万5啦。
规费=证管费+证券交易经手费
（1）证管费：成交金额的0.002% ，买卖双向收取，由证券公司代收后交给中国证监会。
（2）证券交易经手费：A股，按成交金额的0.00341%双向收取。由证券公司代收后交给证券交易所。点评：经手费由原来的万0.487下调到万0.341啦。
过户费:这是指股票成交后，更换户名所需支付的费用。上海和深圳都进行收取，此费用按成交金额的0.001%收取。由证券公司代收后交给中国证券登记结算中心。点评：早于过户费和印花税就下调了，由原来的万0.2减半，现在只收完0.1。
券商交易佣金: 最高不超过成交金
额的0.3%，最低5元起，单笔交易佣金不满5元按5元收取，买卖都收，由证券公司收取。
交易佣金是券商唯一有定价空间的一块，证券会的规定是“最低5元起，最高不超过成交金额的0.3%”。
所以券商的成本是万0.641！！


<a id="卸载腾讯云服务器ydservice云镜"></a>
# 卸载腾讯云服务器ydservice云镜
https://www.sohu.com/a/638194132_242207


<a id="启动parallelsdesktop之后macos没声音的问题"></a>
# 启动ParallelsDesktop之后macOS没声音的问题
1.在 Parallels Desktop 的控制中心，进入对应系统配置页面。
2.打开「硬件 — CPU 与内存 — 高级」选项：
3.将虚拟机监控程序修改为「Apple」，并保存。

4.打开系统「终端 Terminal」软件，并执行以下命令：
sudo launchctl stop com.apple.audio.coreaudiod && sudo launchctl start com.apple.audio.coreaudiod

若系统版本低于 macOS Catalina 10.15.3，请使用 kill coreaudiod 命令。

如果以上步骤完成并保存之后，发现无法打开虚拟机，提示如下：

目前问题暂时无法解决，只能将前面的「虚拟机监控程序」改回「Parallels」。

链接：https://www.jianshu.com/p/c138c9688869


<a id="在-macos-bigsur-monterey等以上系统上关闭lcd-平滑字体"></a>
# 在 macOS-BigSur-Monterey等以上系统上关闭LCD 平滑字体

defaults -currentHost write -g AppleFontSmoothing -int 0

0 是最细，1 是中等，2 是恢复原始的粗细


<a id="在macoscatalina下安装macosmojave作为双系统"></a>
# 在macOSCatalina下安装macOSMojave作为双系统
参考链接：
https://zhuanlan.zhihu.com/p/92791987
降级准备工作
1、退出iCloud和查找我的电脑
2、关闭sip和安全性能和引导-在恢复界面修改-低安全性和允许外界介质
3、关闭系统的时间自动更新-也可重设时间
4、安装过程关闭Wi-Fi按钮 菜单栏上
——
Catalina降级Mojave错误需修改时间代码
10.10：date 122014102015.30
10.11：date 0201010116
10.12：date 010514102017.30
10.13：date 0101012018.30

10.14：date 0101012018.30
10.15：date 121212122019

11.0：date 121212122020

10.12 macOS Sierra：date 010514102017.30
10.13 macOS High Sierra：date 062614102014.30

10.14 macOS Mojave：date 122014102015.30
10.15 macOS Catalina：date 072614102019

11 macOS Big Sur：date 121212122020
12 macOS Monterey：date 121212122021
———————————————
专属
sudo date 122014102015.30
date 122014102015.30
date 032208102015.20
date 0201010116
date 062614102014.30

date 102013142018.20
date 072614102019
date 121212122019
date 0101012018.30

https://mp.weixin.qq.com/s/uG9koTJ2LvArwBvXyOKQoA

https://zhuanlan.zhihu.com/p/92791987

<a id="备用网盘"></a>
# 备用网盘
resilio sync
Sync
filen
internxt


<a id="天翼网关超级密码"></a>
# 天翼网关超级密码
管理员账号：telecomadmin 
密码：nE7jA%5m 
网址：http://192.168.1.1 :8080


<a id="如何下载和安装macos"></a>
# 如何下载和安装macOS

https://support.apple.com/zh-cn/102662


<a id="如何在iphone上访问mac的共享文件夹？"></a>
# 如何在iPhone上访问Mac的共享文件夹？
● 前往 Mac 中的「系统偏好设置」-「共享」-「高级」；
●在「高级」选项中，勾选 SMB 协议，随后为共享文件目录选择一个用户，可以更好地保护文件；
●在「共享」中可以查看当前电脑的名称，以「.local」为结尾的名称会随着 IP 地址而变动。
●设置完成共享文件夹与权限后，前往 iPhone、iPad 的「文件」应用；
●轻触「连接服务器」；
●输入服务器名称；
如：TaiRan-Mac.local
Windows电脑同上，如：bellyling.local
●选择注册用户，并填写管理员账户与密码；
●就可以在 iPhone 或 iPad 上访问 Ｍａｃ 的共享文件夹，可以执行复制粘贴等多种操作。

<a id="安卓通过局域网快速读取macos共享的文件"></a>
# 安卓通过局域网快速读取macOS共享的文件
macOS 配置
创建用户
系统设置 -> 用户与群组 -> 添加账号（需要输入账号密码） -> 填写以下表单信息：
新账号：仅限共享
全名：（随意取一个名称，例如：共享账号）
账号名称：（随意取一个名称，例如：share）
密码：（随意取一个密码：例如：share123456）
确认密码：（再次重复密码）
密码提示：（随意取一个提示，例如：账号名称+123456）
点击“创建用户”按钮创建用户。
配置要共享的文件夹
系统设置 -> 通用 -> 共享 -> 点击“文件共享”最右边 i 图标
在弹出的窗口中，点击“选项”按钮 ->
在弹出的窗口中，勾选“使用SMB来共享文件和文件夹” ->
再勾选之前创建的账号 ->
点击“完成”。
此时文件共享已打开。
点击“共享文件夹”下面的+按钮 ->
双击打开"用户->
共享"文件夹 ->
点击窗口下面“新建文件夹”创建一个 "share" 文件夹 ->
单击“share” 文件夹并点击“添加”按钮。
最后点击“完成”按钮关闭弹窗。
至此，macOS的配置已完成。下面开始用安卓手机连接macOS以便读取文件。
安卓手机连接macOS
确保安卓和macOS在统一局域网。
打开系统内置的“文件管理”app ->
点击浏览Tab ->
点击“网络邻居” ->
点击设备列表中表示macOS的设备 ->
在弹窗中输入之前新建的账号的用户名和密码（share, share123456） ->
点击“确定”按钮连接设备。
连接成功后便会看到之前新建的“share”文件夹了，之后便可以将要共享的文件放到此文件夹以便安卓设备可以读取。
提示
在上面的步骤中，也可以不创建新的账号，而使用默认的管理员账号；也可以不创建“share”文件夹，而是选择已存在任意位置的文件夹。
但从安全的角度看，不建议这么做。

<a id="宝塔重置密码"></a>
# 宝塔重置密码

 cd /www/server/panel && btpython tools.py panel 新的密码

<a id="宝塔面板当前系统防火墙为iptables不支持停止"></a>
# 宝塔面板当前系统防火墙为iptables不支持停止
问题：关闭面板防火墙，提示当前系统防火墙为iptables，不支持停止。且防火墙功能失效。
解决方案：安装ufw
安装好后关闭开启防火墙即可生效。
如果只是面板防火墙失效，也可以用这个方法解决。

<a id="局域网创建mac和windows11共享文件夹"></a>
# 局域网创建Mac和Windows11共享文件夹

参考资料
https://juejin.cn/post/7240427838343643191?searchId=202404182247527C7059701ECB892792AA

官方指南
https://support.apple.com/zh-cn/guide/mac-help/mchlp1659/10.15/mac/10.15


<a id="常用网址大全"></a>
# 常用网址大全
Mac软件下载
https://appstorrent.ru
https://www.macbl.com
————
https://www.macenjoy.net
https://www.digit77.com
https://macapp.org.cn
https://www.imacso.com
—————
Mac图标下载
https://macosicons.com
——————
科学上网
https://v2-free.github.io
https://v2free.net
https://go.tofly.cyou/user
https://go.runba.cyou/user
——————
迅雷4.1.1（65050）下载
http://yangtai.xunlei.com/?cat=44&paged=2
————————
家谱制作软件
Mac-FamilyTree
Windows-GenoPro
————
电影电视剧下载
https://www.xl720.com
https://www.mp4us.com
http://www.domp4.icu
Domp4.cc
http://ddys.tv
https://ddys.pro
https://ddys.info
—
颜色转换工具
http://tool.vpsche.com/hexrgb/
—
在线ps
https://www.photopea.com


<a id="广东电信宽带测速地址"></a>
# 广东电信宽带测速地址
https://10000.gd.cn/?6ylpqNiaaakM=1697602220843#/speed


<a id="开机启动项丢失，grub界面查找启动项"></a>
# 开机启动项丢失，grub界面查找启动项
电脑双硬盘装完ubuntu和windows开机没有引导菜单选项_win10 ubuntu双系统开机没有选择-CSDN博客


<a id="mac显示隐藏恢复隐藏文件"></a>
# Mac显示隐藏恢复隐藏文件
显示隐藏文件：
defaults write com.apple.finder AppleShowAllFiles true
killall Finder
恢复隐藏文件：
defaults write com.apple.finder AppleShowAllFiles false
killall Finder

<a id="新水星路由器网关登录地址"></a>
# 新水星路由器网关登录地址
melogin.cn
http://192.168.0.1

<a id="mac隐藏显示文件、文件夹、应用程序"></a>
# Mac隐藏/显示文件、文件夹、应用程序
隐藏文件/文件夹命令：
chflags hidden (文件/文件夹的相对或绝对路径)
显示文件/文件夹命令：
chflags nohidden (文件/文件夹的相对或绝对路径)
隐藏应用程序
sudo chflags -h hidden (应用程序的相对或绝对路径)
显示隐藏的应用程序
sudo chflags -h nohidden (应用程序的相对或绝对路径)
服务器测速网站
https://www.speedtest.net

<a id="服务器的上行带宽和下行带宽是什么意思？"></a>
# 服务器的上行带宽和下行带宽是什么意思？

对于服务器带宽，想必大家都不会陌生。但提及“上行带宽”与“下行带宽”，或许有些人会感到些许迷茫。今天，我们就来详细解读一下这两者之间的奥秘。
简而言之，上行带宽可视为“上传”带宽，即数据从云服务器流出的带宽；而下行带宽则是“下载”带宽，即数据流入云服务器的带宽。这种流向的区分，是理解上行与下行带宽的关键。
在实际应用中，我们购买的云服务器带宽通常是指上行带宽。以在八艾云购买的一台10M公网带宽的服务器为例，这里的10M便是指上行带宽。换算成实际的下载速度，即用户从云服务器下载文件到本地的速度，约为1280KBps。这个上行带宽，是用户根据实际需求付费购买的。
而下行带宽，情况则有所不同。当我们浏览网页或上传文件时，数据会流入云服务器，这便产生了下行带宽的流量。以网页大小为50kb为例，假设每秒有1000人在线用户上传文件到云服务器，那么云服务器每秒便会接收50000kb的流量。这部分下行带宽流量，通常是免费的，并且在实际应用中，其数值往往远大于上行带宽。
我们日常所说的200M、500M宽带等，主要指的是下行带宽。这些数值代表了我们的网络接入速度，即我们从网络下载数据到本地的速度。
总结来说，上行带宽与下行带宽在云服务器中扮演着不同的角色。上行带宽决定了我们从服务器下载文件的速度，是我们实际购买的带宽；而下行带宽则决定了服务器接收数据的速度，通常是免费的且数值较大。理解这两者的区别，有助于我们更好地选择和管理云服务器带宽，以满足业务需求。

<a id="测dns泄漏网站"></a>
# 测dns泄漏网站
https://ipleak.net


<a id="淋浴软管尺寸-内6mm外8mm"></a>
# 淋浴软管尺寸 内6mm外8mm

<a id="电信路由器登录网址和账号"></a>
# 电信路由器登录网址和账号
192.168.1.1:8080

访问控制 -- 密码

访问路由器通过两个用户名来控制: telecomadmin和useradmin。 
用户名"telecomadmin"可以不受限制地浏览和修改路由器。 
用户名"useradmin"可以访问路由器，浏览配置和统计表。 
useradmin对应密码：3n3fk
telecomadmin对应密码：nE7jA%5m
注意：用户名和密码只能在16个字符以内,且不能包含空格。


电信 超级管理员账号：telecomadmin 超级管理员密码：nE7jA%5m或admintelecom
移动 超级管理员账号：CMCCAdmin 超级管理员密码：aDm8H%MdA
联通 超级管理员账号：CUAdmin 超级管理员密码：aDm8H%MdA或CUAdmin

<a id="端口打不开显示400-bad-request"></a>
# 端口打不开显示400 Bad Request
将“http://IP：端口号”改为
"https:///P:I#D≥"
400 Bad Request

<a id="linux查看dns"></a>
# Linux查看DNS
这里，我们可以用SSH工具链接服务器，然后用cat命令或less命令来查询DNS服务器IP地址。
cat /etc/resolv.conf

修改文件里面的dns(最好别改，会登录不上）
然后重启服务器

腾讯云默认 DNS 为：183.60.83.19，183.60.82.98，若不使用腾讯云默认 DNS，将无法使用私有域解析 Private DNS 提供的服务。如需修改，请参见 获取内网 IP 地址和设置 DNS。

<a id="简书贝交易网站"></a>
# 简书贝交易网站
jianshubei.com
账户：

<a id="翻墙配置终极版本（debian-vless）"></a>
# 翻墙配置终极版本（debian-vless）
https://233boy.com/sing-box/sing-box-server/
https://233boy.com/sing-box/sing-box-script/

Debian 12系统

<a id="腾讯云服务器在重启之后出现连接不上的问题"></a>
# 腾讯云服务器在重启之后出现连接不上的问题

 不知道大家有没有代码调崩之后连接不上云端最后重启云服务器的经历，我在重启云服务器之后就无法使用xshell进行连接，22端口等也打开了，最后问客服知道是网卡问题，输入sudo dhclient 就可以解决（是在云服务器平台提供的vnc登录中输入）

原文链接：https://blog.csdn.net/xiyun_king/article/details/138353712

<a id="苹果mac网络共享文件夹添加到访达侧边栏"></a>
# 苹果mac网络共享文件夹添加到访达侧边栏

任意位置新建一个文件夹 得到一个 未命名文件夹 。右键点击 未命名文件夹 选择“制作替身”
得到 未命名文件夹的替身 右键点击 未命名文件夹的替身 选择 “显示简介”
进去以后会看见“原身”旁边指向的是当前文件夹位置 点击“选择新的原身”路径选择你所需要的网络文件夹。就可以拖拽到侧边栏了。有几个要点要注意下：
我nas选择的是afp方式访问nas 所以能看见的都是在nas里面设置的允许everyone访问的文件夹
mac还有一种方式访问网络文件夹就是 command+k 然后输入局域网地址 这种方式的文件夹添加以后重启后会失败。应该是我nas设置到了什么，每次通过这个方式访问都需要用户名和密码。

参考资料：https://zhuanlan.zhihu.com/p/585090434?utm_id=0

<a id="苹果电脑mac快速关闭一个软件打开的多个窗口（如打开100个备忘录窗口）"></a>
# 苹果电脑mac快速关闭一个软件打开的多个窗口（如打开100个备忘录窗口）
1选择需要关闭的软件。
2按住键盘的option⌥+command⌘，同时点击关闭窗口按钮。
3即可关闭所有窗口。

<a id="路由器相关知识等一系列问题"></a>
# 路由器相关知识等一系列问题

一般如果宽带猫开启了路由功能，路由器如果设置为PPPOE上网，那么光猫连接路由器wan口将无法上网，一般将路由器的上网模式改为动态上网即可。由于光猫连接路由器lan口，路由器被当作无线交换机使用，所以可以正常上网。如果光猫采用桥接模式，没有开启路由功能，一般还是需要连接路由器wan口，通过pppoe拨号上网。

光猫开启路由功能，路由器需设置为动态IP上网


一般情况下如果光猫开启了路由功能，一般路由器就不用设置宽带账号和密码拨号上网了，如果使用pppoe模式上网，光猫连接路由器wan口，是无法正常联网的，一般将路由上网模式改为动态ip，就可以正常上网了。

光猫开启路由功能，连接路由器lan口，路由器作为无线交换机使用


一般光猫开启了路由功能，相当于一台路由器，而将光猫连接到路由器lan口，相当于路由器的级联，路由器将作为无线交换机使用，可以正常上网，且和光猫处于同一局域网。
光猫的路由功能较弱，一般建议改为桥接模式，使用路由器拨号上网

虽然目前主流的光猫都支持路由功能，但光猫路由功能相当较弱，如果对于网络传输品质和速度要求较高，建议让电信公司将光猫改为桥接模式，使用路由器直接拨号上网。

http://www.qqdaili.net/news/topic-8244-1-1.html

去年在家自己想加一个路由接机顶盒，从光猫LAN口加了条网线，怎么配置，就是连不了网，开始没想到光猫是桥接模式，搞了好久，后来想到是没换成路由器模式，不好加LAN口，只好打电话叫师傅来改成了路由器模式[捂脸]一下子搞定了，要不然就只能一个Iptv和一个LAN口，郁闷到死！还好师傅二话不说麻溜滴就来了，要不然匆匆忙忙几天假期还真装不完网线！

光猫改桥接，不影响IPTV吗？

不影响IPTV,但是光猫自带的有多个LAN口你想再加网线，就必须路由器模式了，要不然只有一个接口有信号[捂脸]

方案1:使用光猫拨号，光猫做主路由器，然后连接自购的无线路由器的lan口，使用路由器的WIFI功能
方案2:光猫改桥接模式，使用自购的路由器拨号，自购路由器作为主路由器


<a id="路由器无线桥接-方法"></a>
# 路由器无线桥接 方法
参考资料：
http://www.it528.com/skill/3490.html

https://zhidao.baidu.com/question/1304907986512681739.html

<a id="路由器桥接模式设置方法"></a>
# 路由器桥接模式设置方法
https://zhuanlan.zhihu.com/p/358075010

https://zhuanlan.zhihu.com/p/607518654

https://www.luyouqi.com/shezhi/6313.html

<a id="路由器模式-连接区别"></a>
# 路由器模式 连接区别
桥接模式-wan口连接
路由模式-lan口连接

<a id="路由器登录地址"></a>
# 路由器登录地址
电信天翼路由器地址
http://192.168.1.1:8080/login.html

水星路由器地址
http://melogin.cn/

<a id="重置macos程序坞以及defaults命令用法"></a>
# 重置macOS程序坞以及defaults命令用法

defaults delete com.apple.dock && killall Dock

参考链接：https://zhuanlan.zhihu.com/p/393397480?utm_id=0

<a id="键盘没坏，电脑键盘突然失灵，打不出字怎么办？"></a>
# 键盘没坏，电脑键盘突然失灵，打不出字怎么办？

https://blog.csdn.net/zhangzhenyan19930312/article/details/116525767

<a id="静态博客站点生成器"></a>
# 静态博客站点生成器
pelican
mkdocs
docsidy

