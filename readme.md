#### 说明

自定义的openwrt编译配置，自动编译配置基于[P3TERX/Actions-OpenWrt](https://github.com/P3TERX/Actions-OpenWrt)进行修改。

#### 安装插件

| 插件名称                  | 功能                       | 备注                                                                            | 是否内置 |
|:---------------------:|:------------------------:|:-----------------------------------------------------------------------------:|:----:|
| luci-app-adguardhome  | AdGuard Home广告过滤         | feeds.conf.default中添加：src-git https://github.com/kenzok8/openwrt-packages.git | 否    |
| luci-app-arpbind      | arp绑定                    |                                                                               | 是    |
| luci-app-autoreboot   | 计划重启功能                   |                                                                               | 是    |
| luci-app-ddns         | ddns支持                   |                                                                               | 是    |
| luci-app-diskman      | 磁盘管理工具                   |                                                                               | 是    |
| luci-app-docker       | docker支持                 |                                                                               | 是    |
| luci-app-dockerman    | Docker管理界面               |                                                                               | 是    |
| luci-app-filetransfer | 文件传输                     |                                                                               | 是    |
| luci-app-firewall     | 防火墙                      |                                                                               | 是    |
| luci-app-frpc         | 内网穿透工具frpc客户端            |                                                                               | 是    |
| luci-app-guestwifi    | 访问wifi支持                 |                                                                               | 是    |
| luci-app-hd-idle      | 硬盘自动休眠                   |                                                                               | 是    |
| luci-app-nlbwmon      | 带宽监控                     |                                                                               | 是    |
| luci-app-nps          | 内网穿透工具nps                |                                                                               | 是    |
| luci-app-openclash    | openclash                | feeds.conf.default中添加：src-git https://github.com/kenzok8/openwrt-packages.git | 否    |
| luci-app-qos          | qos                      |                                                                               | 是    |
| luci-app-samba4       | samba支持                  |                                                                               | 是    |
| luci-app-statistics   | 流量监控                     |                                                                               | 是    |
| luci-app-sqm          | 智能流控                     |                                                                               | 是    |
| luci-app-turboacc     | TurboAcc加速               |                                                                               | 是    |
| luci-app-ttyd         | 命令行终端                    |                                                                               | 是    |
| luci-app-vssr         | helloworld               | 取消feeds.conf.default中的helloworld注释                                            | 否    |
| luci-app-wifischedule | wifi计划任务                 |                                                                               | 是    |
| luci-app-wol          | 网络唤醒                     |                                                                               | 是    |
| luci-app-zerotier     | Zerotier虚拟局域网            |                                                                               | 是    |
| luci-theme-argon      | Argon主题                  |                                                                               |      |
| odhcp6c               | dhcpv6客户端                | 位置：Network                                                                    |      |
| odhcpd-ipv6only       | dhcpv6服务端                |                                                                               |      |
| luci-proto-ipv6       | ipv6协议支持                 | 位置：LuCI->Protocols                                                            |      |
| luci-proto-ppp        | ppp/pppoe/pppoa/pptp协议支持 |                                                                               |      |
| zsh                   | zsh命令行                   | 位置：Utilities -> Shells                                                        |      |
| fdisk                 | mbr分区工具                  | 位置：Utilities -> disc                                                          |      |
| gdisk                 | gbt分区工具                  |                                                                               |      |
| I18N                  | 管理界面翻译相关                 | 位置：LuCI->Modules->Translations                                                |      |
