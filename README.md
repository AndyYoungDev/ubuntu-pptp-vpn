# pptp
Ubuntu pptp搭建脚本
* 修改账号密码 /etc/ppp/chap-secrets
* 修改网卡 iptables -t nat -A POSTROUTING -s 192.168.2.0/24 -d 0.0.0.0/0 -o eth0 -j MASQUERADE
