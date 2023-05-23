# 中文 | [English](https://github.com/DHDAXCW/NanoPi-R5S-2021/blob/main/EngLish.md)
# x86-x64

# 目录

[一、简介](#一简介)

[二、固件](#二固件)

[三、资源链接](#三资源链接)

[四、插件展示](#四插件展示)

[五、鸣谢](#五鸣谢)

# 一、简介

该项目从[DHDAXCW/OpenWRT_x86_x64](https://github.com/DHDAXCW/OpenWRT_x86_x64)进行定制，添加5G模块支持和个人定制化

# 二、固件

## 说明

- 支持大多数5G模块
- 支持5G模块使用USB和PCIE通信
- 支持网卡MT7921系列
- 完美支持AW7916大功率网卡（minipcie电流要求3a以上才不会掉卡）

## 类型

### 6.x内核

- 完整版（full）：5G支持+网卡支持+多个插件
- 精简版（simplify）：5G支持+网卡支持+OpenClash+AD Guardhome等少量常用插件

### 5.x内核

- 特制版（special）：信号插件+5G支持+网卡支持+OpenClash+AD Guardhome等少量常用插件

## 下载

- 固件下载地址：https://github.com/Siriling/OpenWRT_x86_x64/releases

# 三、资源链接

- 5G模组拨号脚本：[点击查看](https://github.com/Siriling/OpenWRT_x86_x64/tree/main/tools/5G%E6%A8%A1%E7%BB%84%E6%8B%A8%E5%8F%B7%E8%84%9A%E6%9C%AC)

# 四、插件展示
![plugins](images/plugins.png)

# 五、鸣谢

Openwrt 官方项目：

<https://github.com/openwrt/openwrt>

Lean 大的 Openwrt 项目：

<https://github.com/coolsnowwolf/lede>

immortalwrt 的 OpenWrt 项目：

<https://github.com/immortalwrt/immortalwrt>

P3TERX 大佬的 Actions-OpenWrt 项目：

<https://github.com/P3TERX/Actions-OpenWrt>

SuLingGG 大佬的 Actions 编译框架 项目：

https://github.com/SuLingGG/OpenWrt-Rpi
