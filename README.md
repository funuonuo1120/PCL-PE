# PCL PE

基于 **PCL Living Fork 1.5.1**（C# / .NET 10）源码换底重制的 **Plain Craft Launcher PE** 启动器发行仓库。本仓库不存放源码，仅作为官方下载与自动更新清单的分发渠道。

## 下载

前往 [Releases](https://github.com/funuonuo1120/PCL-PE/releases) 页面下载最新版本的 exe。启动器内置自动更新：每次启动会静默检查新版本，经你确认后自动下载、SHA256 校验并重启完成更新。

## 主要特性

- **陶瓦联机**：顶栏联机页 + 内嵌联机内核，附推荐联机工具（uu云联机 / MCTier / 樱花内网 / Lolia FRP）
- **主题色相全解锁**：彩虹条随意拖动换色，导航栏与全局实时跟随
- **LF 原生功能**：版本选择/版本设置、按键绑定设置、回收站、还原点、克隆版本、自定义主页等
- **自更新**：清单驱动，多下载源（GitHub + 镜像）自动轮试，SHA256 校验，静默自替换

## 更新清单

`update.json` 为启动器自动更新使用的版本清单，包含最新版本号、更新说明、文件哈希与下载地址。更新发布时随 Release 一并更新。

## 运行要求

- Windows 10 及以上（64 位）
- [.NET 10 桌面运行时 (x64)](https://dotnet.microsoft.com/zh-cn/download/dotnet/10.0)

## 许可证与致谢

- 本项目基于 [PCL Living Fork](https://github.com/PCL-Community/PCL-Living-Fork) 与 [Plain Craft Launcher 2](https://github.com/Hex-Dragon/PCL2)（MPL-2.0）修改，遵循 **[Mozilla Public License 2.0](LICENSE)** 开源。
- 如需获取对应源码，请参考上述上游仓库；PE 相关修改如你也需要，欢迎联系作者。
- 启动器免费，无任何付费解锁内容；下载请认准本仓库 Releases，谨防捆绑。

## 免责声明

本启动器与 Mojang、Microsoft 无关。Minecraft 版权归 Mojang Studios 所有。使用本启动器产生的一切后果由使用者自行承担。
