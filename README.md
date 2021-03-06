# 使用 Github Actions 在线编译 NanoPi-R2S 固件

## 说明
* IP: 192.168.2.1
* 密码: password

## 特色
* 支持 RTL8821CU 芯片的 USB WiFi 设备，已知支持列表：
    - [COMFAST 726B](https://u.jd.com/DOkkhX)
    - [COMFAST CF-759BF](https://u.jd.com/C2ivH7)
* 集成 [frainzy1477/luci-app-clash](https://github.com/frainzy1477/luci-app-clash) 及其 clash bin（CONFIG_PACKAGE_luci-app-clash 默认没开启）
* 集成 [vernesong/OpenClash](https://github.com/vernesong/OpenClash) 及其 clash bin
* 集成 [rufengsuixing/luci-app-adguardhome](https://github.com/rufengsuixing/luci-app-adguardhome)（CONFIG_PACKAGE_luci-app-adguardhome 默认没开启）
* 集成 [coolsnowwolf/packages](https://github.com/coolsnowwolf/packages) 与 [coolsnowwolf/luci](https://github.com/coolsnowwolf/luci)
* 更新 [jerrykuku/luci-theme-argon](https://github.com/jerrykuku/luci-theme-argon)
* 集成最新实时监控 Netdata v1.20.0

## 用法
Fork 到自己的账号下，配置 `r2s-rk3328-config` 文件中的功能开关，编辑文件 `CHANGELOG.md` 触发编译动作。

## 注意
产品发布初期，官方代码每天都在变，遇到无法编译时，请过来查看 `.yml` 与 `config` 最新异动。

## 参考
* [使用Github的Actions功能在线编译NanoPi-R1S固件（包含H5和H3）](https://totoro.site/index.php/archives/70/)
* [skytotwo/NanoPi-R1S-Build-By-Actions](https://github.com/skytotwo/NanoPi-R1S-Build-By-Actions)
* [klever1988/nanopi-openwrt](https://github.com/klever1988/nanopi-openwrt)
* [maxming2333/NanoPi-R2S](https://github.com/maxming2333/NanoPi-R2S)
* [soffchen/NanoPi-R2S](https://github.com/soffchen/NanoPi-R2S)
