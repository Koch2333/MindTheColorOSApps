# MindTheColorOSApps
OxygenOS 本地化补全模块

**提示：由于本人是高三牲，学业繁忙以及功能实现需要花费大量精力，故无法及时维护，还请谅解。**

一个用于给 OxygenOS 补齐 ColorOS 本地化功能的模块，并同时支持多款一加设备。

注意：本模块并不适用于修复一加国行机型与外版机型的硬件差异带来的驱动问题


## 功能
- 公交卡/门禁卡模拟功能 (OPPO钱包)
- 将 应用商店及天气等基础系统应用替换为国内版
- 更改build.prop型号为对应国内机型

**注: 此为Lite版基本功能，完整版(full)将包含以上所有功能并集成更多应用**

## 处理中
- [ ] 钱包app无法添加门禁卡
- [ ] OnePlus AI 本地化功能
- [ ] action.sh 适用操作支持

## 使用要求
- 一台已解锁 Bootloader (引导加载程序) 并运行 OxygenOS 的一加设备
- 使用支持模块系统的root方案，如Magisk或KernelSU

**KernelSU 3.0及以上用户请使用Magic Mount的原模块，Hybrid Mount用户需要使用Magic Mount方式挂载应用本模块**
- 使用OxygenOS 16及以上版本 (目前仅计划向下适配至 OxygenOS 15，如有其他需求请通过issues反馈)

## 感谢
- [酷安@天伞桜](http://www.coolapk.com/u/540690) 的原模块补全思路
- [Magisk](https://github.com/topjohnwu/Magisk/) 的模块支持
