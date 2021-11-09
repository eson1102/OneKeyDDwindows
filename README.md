# 使用说明
脚本内容来自互联网

25合一系统密码：
1、CentOS 7.7 (已关闭防火墙及SELinux，默认密码Pwd@CentOS)
2、CentOS 7 (默认密码cxthhhhh.com)
3、CentOS 8 (默认密码cxthhhhh.com)
4、CentOS 6 (默认密码Minijer.com)
5、Debian 11 (默认密码Minijer.com)
6、Debian 10 (默认密码Minijer.com)
7、Debian 9 (默认密码Minijer.com)
8、Debian 8 (默认密码Minijer.com)
9、Ubuntu 20.04 (默认密码Minijer.com)
10、Ubuntu 18.04 (默认密码Minijer.com)
11、Ubuntu 16.04 (默认密码Minijer.com)
12、Windows Server 2019 (默认密码cxthhhhh.com)
13、Windows Server 2016 (默认密码cxthhhhh.com)
14、Windows Server 2012 (默认密码cxthhhhh.com)
15、Windows Server 2012 Lite (默认密码nat.ee)
16、Windows Server 2008 (默认密码cxthhhhh.com)
17、Windows Server 2008 Lite (默认密码nat.ee)
18、Windows Server 2003 (默认密码cxthhhhh.com)
19、Windows Server 2003 Lite (默认密码WinSrv2003x86-Chinese)
20、Windows 10 LTSC Lite (默认密码www.nat.ee)
21、Windows 7 x86 Lite (默认密码Windows7x86-Chinese)
22、Windows 7 Ent Lite (默认密码nat.ee)
23、Windows 7 Ent Lite (UEFI支持甲骨文)(默认密码nat.ee)
24、Windows Server 2008 Lite (UEFI支持甲骨文)(默认密码nat.ee)
25、Windows Server 2012 Lite (UEFI支持甲骨文)(默认密码nat.ee)
99、自定义镜像

#安装重装系统的前提组件:
Debian/Ubuntu:

apt-get install -y xz-utils openssl gawk file wget screen && screen -S os
RedHat/CentOS:

yum install -y xz openssl gawk file glibc-common wget screen && screen -S os
如果出现异常，请刷新Mirrors缓存或更换镜像源。
RedHat/CentOS:

yum makecache && yum update -y
Debian/Ubuntu:

apt update -y && apt dist-upgrade -y


# 1 chmod a+x AutoReinstall.sh 

# 2 bash AutoReinstall.sh
