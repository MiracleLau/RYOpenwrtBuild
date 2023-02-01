#### 说明

自定义的openwrt编译配置

#### 安装插件

| 插件名称                 | 功能                       | 备注                                                                  |
| -------------------- | ------------------------ | ------------------------------------------------------------------- |
| luci-app-adguardhome | AdGuard Home广告过滤         | 可添加https://github.com/liuran001/openwrt-packages到feeds.conf.default |
| luci-app-autoreboot  | 计划重启功能                   |                                                                     |
| luci-app-ddns        | DDNS                     |                                                                     |
| luci-app-docker      | Docker支持                 |                                                                     |
| luci-app-dockerman   | Docker管理界面               |                                                                     |
| luci-app-passwall2   | passall2上网工具             | https://github.com/xiaorouji/openwrt-passwall2                      |
| luci-app-frpc        | 内网穿透工具frpc客户端            |                                                                     |
| luci-app-npc         | 内网穿透工具npc客户端             |                                                                     |
| luci-app-hd-idle     | 硬盘休眠                     |                                                                     |
| luci-app-nlbwmon     | 带宽监控                     |                                                                     |
| luci-app-statistics  | 流量监控                     |                                                                     |
| luci-app-sqm         | 智能流控                     |                                                                     |
| luci-app-turboacc    | TurboAcc加速               |                                                                     |
| luci-app-ttyd        | 命令行终端                    |                                                                     |
| luci-app-wol         | 网络唤醒                     |                                                                     |
| luci-app-zerotier    | Zerotier虚拟局域网            |                                                                     |
| luci-theme-argon     | Argon主题                  |                                                                     |
| odhcp6c              | dhcpv6客户端                | 位置：Network                                                          |
| odhcpd-ipv6only      | dhcpv6服务端                |                                                                     |
| luci-proto-ipv6      | ipv6协议支持                 | 位置：LuCI->Protocols                                                  |
| luci-proto-ppp       | ppp/pppoe/pppoa/pptp协议支持 |                                                                     |
| zsh                  | zsh命令行                   | 位置：Utilities -> Shells                                              |
| fdisk                | mbr分区工具                  | 位置：Utilities -> disc                                                |
| gdisk                | gbt分区工具                  |                                                                     |
| I18N                 | 管理界面翻译相关                 | 位置：LuCI->Modules->Translations                                      |
| kmod-fs-*            | 文件系统支持                   | 位置：Kernel modules->FileSystems，支持文件系统见[文件系统](#支持文件系统)章节             |



#### 支持文件系统

- antfs

- btrfs

- cifs

- configfs

- exfat

- ext4

- nfs

- nfsd

- squashfs

- vfat

- xfs
