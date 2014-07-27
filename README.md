what
============

* 使用shell管理自己的手机 增强手机功能

how
===========

* 手机已经root
* 安装SupeUser
* 安装busybox
* 安装OI文件管理器
* 安装ssh/sftp server 设置ssh认证需要的公钥(免密码登陆)

```
ssh root@192.168.1.102 "uname -a"
```
* 结果
```
SSHD Server
Linux localhost 3.0.8-00821-g6fd9b1d #1 SMP PREEMPT Sat Aug 10 20:48:08 CST 2013 armv7l GNU/Linux
```

* 检查系统的shll
```
echo $SHELL
/system/bin/sh
```
