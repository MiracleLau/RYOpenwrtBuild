#### 说明

自定义的openwrt编译配置，自动编译配置基于[P3TERX/Actions-OpenWrt](https://github.com/P3TERX/Actions-OpenWrt)进行修改。

#### 安装插件

|        插件名称         |             功能             |                 备注                  |
| :---------------------: | :--------------------------: | :-----------------------------------: |
|    luci-app-arpbind     |           arp绑定            |                                       |
|   luci-app-autoreboot   |         计划重启功能         |                                       |
|      luci-app-ddns      |           ddns支持           |                                       |
|    luci-app-diskman     |         磁盘管理工具         |                                       |
|     luci-app-docker     |          docker支持          |                                       |
|   luci-app-dockerman    |        Docker管理界面        |                                       |
|  luci-app-filetransfer  |           文件传输           |                                       |
|    luci-app-firewall    |            防火墙            |                                       |
|      luci-app-frpc      |    内网穿透工具frpc客户端    |                                       |
|   luci-app-guestwifi    |         访问wifi支持         |                                       |
|    luci-app-hd-idle     |         硬盘自动休眠         |                                       |
|    luci-app-nlbwmon     |           带宽监控           |                                       |
|      luci-app-n2n       |             n2n              |                                       |
|      luci-app-nps       |       内网穿透工具nps        |                                       |
|     luci-app-samba4     |          samba支持           |                                       |
|   luci-app-statistics   |           流量监控           |                                       |
|      luci-app-sqm       |           智能流控           |                                       |
|    luci-app-turboacc    |         TurboAcc加速         |                                       |
|      luci-app-ttyd      |          命令行终端          |                                       |
|      luci-app-upnp      |             upnp             |                                       |
| luci-app-wifi-schedule  |         wifi计划任务         |                                       |
|      luci-app-wol       |           网络唤醒           |                                       |
|    luci-app-zerotier    |      Zerotier虚拟局域网      |                                       |
|   luci-theme-neobird    |             主题             |                                       |
|         ds_lite         |          支持dslite          |             位置：Network             |
|         odhcp6c         |         dhcpv6客户端         |             位置：Network             |
|     odhcpd-ipv6only     |         dhcpv6服务端         |                                       |
|       ipv6helper        |         ipv6支持相关         |         位置：Extra packages          |
|     luci-proto-ipv6     |         ipv6协议支持         |         位置：LuCI->Protocols         |
|     luci-proto-ppp      | ppp/pppoe/pppoa/pptp协议支持 |                                       |
|          fdisk          |         mbr分区工具          |        位置：Utilities -> disc        |
|  Chinese translations   |       管理界面翻译相关       |   位置：LuCI->Modules->Translations   |
|      ddns-scripts       |          ddns的脚本          | 位置：Network->IP Addresses and Names |
|        bind-host        |        bind dns客户端        | 位置：Network->IP Addresses and Names |
|    kmod-usb-storage     |       usb存储设备支持        |  位置：Kernel modules -> USB Support  |
| kmod-usb-storage-extras |       usb存储设备支持        |                                       |
|        kmod-usb2        |          usb2.0支持          |                                       |
|        kmod-usb3        |          usb3.0支持          |                                       |
|      kmod-fs-exfat      |      exfat文件系统支持       |  位置：Kernel modules -> Filesystems  |
|      kmod-fs-ext4       |       ext4文件系统支持       |                                       |
|      kmod-fs-ntfs       |       ntfs文件系统支持       |                                       |
|      kmod-fs-ntfs3      |      ntfs3文件系统支持       |                                       |
|      kmod-fs-vfat       |       vfat文件系统支持       |                                       |
