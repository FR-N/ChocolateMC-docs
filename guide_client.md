# 巧克力服务器相关 mod 等安装指南

::: info
前言：本书是对服务器 mod/客户端安装的更详细指南，一般指南看 `/guide` 的第二页即可获取相应软件与 mod。
:::

## 目录

- 条目1. 客户端需求
- 条目2. 关于服务器官方整合包
- 条目3. 主服务器 mod
- 条目4. 子服务器（1.21.1 tacz）必装 mod

---

## 条目1. 客户端需求

本服务器是 1.21.8 leaves 二改服务器，并配置了 viaversion 等一系列插件。虽然在低版本到 1.21.8 都可以进入服务器，但是建议使用 1.21.8 以获得最佳体验。

::: tip
注意：本服务器的子服务器是 1.21.1 的 tacz 服务器。如果您想进入子服务器进行游玩体验，请务必安装 1.21.1 fabric 客户端。
:::

---

## 条目2. 关于服务器官方整合包

服务器目前提供两个推荐版本的客户端整合包，分别为 **1.21.1** 和 **1.21.8**，它们各有特点，请根据需求选用：

- **1.21.1 版本**：相对成熟，原生支持 YSM，并且完美兼容我们配置的 tacz 服务器。
- **1.21.8 版本**：与目前 Chocolate 主服务器的服务端版本相对应，适配度更高。

::: tip 官方整合包下载
点击下方链接即可直接下载预配置好的官方整合包：

- **[1.21.1 tacz 官方推荐整合包](http://ip4.zgwl.eu.org:5244/d/%E4%B8%AD%E7%94%B5NSLS/OPEN/Minecraft/Chocolatemodpack/1.21.1tacz%201.21.1tacz-Chocolate%20V1.0.3.20260630_base.zip?sign=DfBvggfwkXnHM91ZdRW9OscDoxvkcp1935Xs3x-GChs=:0)** —— 更多的mod多样性
- **[1.21.8 Fabric 官方推荐整合包](http://pan.zgwl.eu.org:5244/d/%E4%B8%AD%E7%94%B5NSLS/OPEN/Minecraft/Chocolatemodpack/1.21.8-Fabric-chocolate-lhx28.zip?sign=Vq3UF-9TxHAEp1O2WO_RgEwaXWOTe9UAa7r9Oto9nTU=:0)** —— 主服务器配合
:::

---

## 条目3. 主服务器 mod

::: tip
服务器开启了很多功能，没有对应的 mod 可能无法完整体验服务器全部功能。
另外可以进入 QQ 群获取他人制作的整合包等。
下面的所有子条目都是自定义安装的参考项目。
:::

### 子条目1. 性能优化 mod（必装，不装极易卡顿）

- [Dynamic FPS (动态 fps)](https://www.mcmod.cn/class/3074.html)
- [EntityCulling (实体渲染优化)](https://www.mcmod.cn/class/3629.html)
- [FerriteCore (铁氧体磁芯)](https://www.mcmod.cn/class/3888.html)
- [Gpu Tape (显存泄漏优化)](https://www.mcmod.cn/class/19415.html)
- [Sodium (钠)](https://www.mcmod.cn/class/2785.html)
- [Sodium Extra (钠·扩展)](https://www.mcmod.cn/class/3701.html)
- [ThreatenGL (切换 opengl 版本)](https://www.mcmod.cn/class/17620.html)
- [Lithium (锂)](https://www.mcmod.cn/class/2292.html)

---

### 子条目2. 优化显示与游戏体验 mod

- AllMusic Client（全服点歌，支持 VIP）
- Yes Steve Model（需 2.6.5 版本）
- Chocolate SLmgr（巧克力服务器定制客户端认证器）

::: tip 专属 Mod 获取
以上三个专用 mod 请前往网盘获取（强烈建议通过此链接下载）：
- **[点击进入网盘获取](https://wwanc.lanzouq.com/b0ko8juob)** （提取码：**chocolate**）
:::

- [Chat Heads (聊天头像)](https://www.mcmod.cn/class/4523.html)
- [Freecam (自由相机)](https://www.mcmod.cn/class/6729.html)
- [IPN (一键背包整理)](https://www.mcmod.cn/class/4104.html)
- [Jade (玉)](https://www.mcmod.cn/class/3482.html)
- 小地图（请自备）
- [Litematica (投影)](https://www.mcmod.cn/class/2261.html)
- [ModMenu (模组菜单)](https://www.mcmod.cn/class/1675.html)
- [Neat (极简血量显示)](https://www.mcmod.cn/class/619.html)
- [Not Enough Crashes (崩溃优化)](https://www.mcmod.cn/class/2441.html)

---

## 条目4. 子服务器必装 mod（不装无法进入）

::: tip
其他 mod 可以参考上方进行配置（建议只安装性能优化 mod 即可）。
如果出现 recipe 包出错，实际上是客户端 mod 与服务器不一致导致的。
:::

::: tip tacz 必备模组 (Fabric) 获取
服务器已打包好 tacz 必备的几个 mod：
- **[点击进入网盘获取](https://wwanc.lanzouq.com/b0ko8juob)** （提取码：**chocolate**）
:::

**备用解决方案：**
如果出现键位冲突导致无法左键，可以安装此修复补丁：
- [Keybind Fix Plus](https://modrinth.com/mod/keybind-fix-plus/versions)

---
Written by lhx28 2026.06.29