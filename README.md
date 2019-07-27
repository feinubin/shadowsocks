# shadowsocks
开源官方：
https://github.com/shadowsocks


Install:

wget --no-check-certificate https://raw.githubusercontent.com/leesiyang/shadowsocks/master/shadowsocks-libev.sh
chmod +x shadowsocks-libev.sh
./shadowsocks-libev.sh 2>&1 | tee shadowsocks-libev.log

使用命令：

启动：/etc/init.d/shadowsocks start

停止：/etc/init.d/shadowsocks stop

重启：/etc/init.d/shadowsocks restart

查看状态：/etc/init.d/shadowsocks status


1、本脚本会始终安装最新版的 Shadowsocks；

2、修改配置文件 /etc/shadowsocks-libev/config.json 同时启用 IPv4 与 IPv6 支持
