![logo](https://raw.githubusercontent.com/johnrosen1/trojan-gfw-script/master/logo.png)
# VPS Toolbox

A powerful Toolbox for Linux VPS.

#### 如何使用
```
apt-get update && apt-get install sudo curl -y && sudo bash -c "$(curl -fsSL https://raw.githubusercontent.com/johnrosen1/vpstoolbox/master/vps.sh)"
```

流量图示:
![flowchart](https://raw.githubusercontent.com/jerrypoma/trojan-gfw-script/master/vpstoolbox.png)

#### 隐私声明:

1. 此项目使用MIT开源协议，欢迎PR.
2. Ip Information is just an indispensable part of this project, all ip information comes from ipinfo.io,no spam related.

#### 友情提示:
1. 请 **以root/sudoer身份运行**(sudo -i)
2. 请 **[先购买一个域名](https://www.namesilo.com/?rid=685fb47qi)** 并 **[完成DNS解析](https://dnschecker.org/)**!
3. 请在控制面板中 **开启TCP端口 [80](https://www.speedguide.net/port.php?port=80) 以及 [443](https://www.speedguide.net/port.php?port=443) 并 关闭 Cloudflare CDN** !
4. For customized certificate , please put it in /etc/trojan/ , no name change required !
5. 请使用一台有至少 **0.5 GB RAM** 以及 **5G 硬盘空间的VPS**. 

### Give it a try ! (Live Demo,随时可能会挂)

[https://www.trojan-gfw.xyz/vpstoolbox.html](https://www.trojan-gfw.xyz/vpstoolbox.html)

#### 特性:

1. 全自动安装并配置 **[NGINX Web Server](https://www.nginx.com/)**
20. 支援全自动安装并配置 **[Trojan-GFW](https://github.com/trojan-gfw/trojan) [Dnscrypt-proxy](https://www.dnscrypt.org/) [Qbittorrent](https://www.qbittorrent.org/) [Bittorrent-Tracker](https://github.com/webtorrent/bittorrent-tracker) [Aria2](https://github.com/aria2/aria2) [Filebrowser](https://github.com/filebrowser/filebrowser) [Netdata](https://github.com/netdata/netdata) [MariaDB](https://mariadb.org/) and [TOR](https://famicoman.com/2018/01/03/configuring-and-monitoring-a-tor-middle-relay/)**
3. 全自动签发,续签,重启服务 [let's encrypt 证书](https://letsencrypt.org/)
4. **支援 [Debian](https://www.debian.org/) [Ubuntu](https://ubuntu.com/)**
16. Random Html Template Choose
17. [完整的IPV6支援](https://en.wikipedia.org/wiki/IPv6)
17. [Full HTTP/2 Support](https://en.wikipedia.org/wiki/HTTP/2)
18. [全自动时间较准](https://www.freedesktop.org/software/systemd/man/timedatectl.html)
19. 全自动掉线重启
20. [全自动检测并卸载阿里云监控](https://www.johnrosen1.com/ali-iso/)
9.  支援 [TCP Turbo](https://github.com/shadowsocks/shadowsocks/wiki/Optimizing-Shadowsocks)
15. 支援 [TLS1.3 ONLY](https://wiki.openssl.org/index.php/TLS1.3)
21. 支援手动更新（Trojan-GFW为全自动更新，binary only）
23. 支援完全/部分卸载
24. And so on...

## If you found it useful , please give a star ,thanks!
