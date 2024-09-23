---
abbrlink: ''
categories: []
date: ''
tags: []
title: 【WARP再次复活】🔥Cloudflare的warp的MAQSUE新协议无限流量,Mac、Win、IOS、安卓全教程细讲,防失联必备
updated: '2024-09-23T14:18:45.020+08:00'
---
**《部署教程说明》**## 🔥Cloudflare的**WARP+** 再次**复活**,**MAQSUE**新协议无限流量

## 🔥**Mac、Win、IOS、安卓**全教程细讲,**防失联必备!**

* 1、下载地址(根据情况下载对应自己的客户端)
  * 官网下载地址: [warp](https://one.one.one.one/zh-Hans/)
    [![vpn-warp](https://am.809098.xyz/img/warp/warp-001.jpg)](https://am.809098.xyz/img/warp/warp-001.jpg)
  *
* 2、电脑客户端
  * **Mac电脑**
    1.打开电脑终端 **(我这里用的是iterm2)** ,然后输入下面命令更换 **新协议MAQSUE**
    SHELL


    | `1`<br/> | `warp-cli tunnel protocol set MASQUE`<br/> |
    | -------- | ------------------------------------------ |

    2.查看 **新协议MAQSUE** 是否生效,生效就重新启动 **WARP** 工具,点启动连接即可

    SHELL

    | `1`<br/> | `warp-cli settings | grep protocol`<br/> |
    | -------- | ---------------------------------------- |

    .[![vpn-warp](https://am.809098.xyz/img/warp/warp-mac-001.jpg)](https://am.809098.xyz/img/warp/warp-mac-001.jpg)
    3.如果出现 **error: unrecognized subcommand protocol** 错的解决方案,打开 **warp** 设置安装 **最新测试版本** ,根据下面图去**打勾**,自动跳出安装页面然**进行安装**,完成安装后再**执行上面的命令**就可以了

    [![vpn-warp](https://am.809098.xyz/img/warp/warp-mac-002.jpg)](https://am.809098.xyz/img/warp/warp-mac-002.jpg)[![vpn-warp](https://am.809098.xyz/img/warp/warp-mac-003.jpg)](https://am.809098.xyz/img/warp/warp-mac-003.jpg)
  * **win电脑**
    1.创建 **mdm.xml** 文件,放到 **C:\\ProgramData\\Cloudflare** 目录下
    PLAINTEXT


    | `1`<br/>`2`<br/>`3`<br/>`4`<br/> | `<dict>`<br/>`    <key>warp_tunnel_protocol</key>`<br/>`    <string>masque</string>`<br/>`</dict>`<br/> |
    | -------------------------------- | ------------------------------------------------------------------------------------------------------- |

    2.重新启动 **warp** 工具后,点开连接即可生效
* 3、手机客户端
  * **苹果手机**[![vpn-warp](https://am.809098.xyz/img/warp/warp-ios-001.jpg)](https://am.809098.xyz/img/warp/warp-ios-001.jpg)[![vpn-warp](https://am.809098.xyz/img/warp/warp-ios-002.jpg)](https://am.809098.xyz/img/warp/warp-ios-002.jpg)[![vpn-warp](https://am.809098.xyz/img/warp/warp-ios-003.jpg)](https://am.809098.xyz/img/warp/warp-ios-003.jpg)[![vpn-warp](https://am.809098.xyz/img/warp/warp-ios-004.jpg)](https://am.809098.xyz/img/warp/warp-ios-004.jpg)[![vpn-warp](https://am.809098.xyz/img/warp/warp-ios-005.jpg)](https://am.809098.xyz/img/warp/warp-ios-005.jpg)
  * **安卓手机**
* 4、**ZeroTrust**用户
  [![vpn-warp](https://am.809098.xyz/img/warp/warp-zt-001.jpg)](https://am.809098.xyz/img/warp/warp-zt-001.jpg)[![vpn-warp](https://am.809098.xyz/img/warp/warp-zt-002.jpg)](https://am.809098.xyz/img/warp/warp-zt-002.jpg)[![vpn-warp](https://am.809098.xyz/img/warp/warp-zt-003.jpg)](https://am.809098.xyz/img/warp/warp-zt-003.jpg)
