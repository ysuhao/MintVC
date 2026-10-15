# Mintaria · 萌音

Windows 实时 AI 变声，声音在本机处理。原项目名称为 MintVC / 萌妹AI变声。

[官网与音色库](https://mintaria.mintryu.com/) · [全部版本与更新记录](https://github.com/ysuhao/Mintaria/releases)

## 一个项目，持续更新

所有历史版本和后续更新统一发布在本仓库的 **Releases** 中。点击页面右上角 **Star** 即可收藏整个 Mintaria 项目，无需为每个版本重复收藏。需要更新通知可选择 **Watch → Custom → Releases**。

本公开仓库提供产品介绍、更新记录与安装包下载。

## 当前下载

- **Mintaria 5.1 正式版**：[GitHub 分卷下载](https://github.com/ysuhao/Mintaria/releases/tag/v5.1.0) · [夸克完整包](https://pan.quark.cn/s/6787c6ca4b10) · [Google Drive 分卷下载](https://drive.google.com/drive/folders/15Aru5Fhy0rrTgSyTeuFYyBDuzLWMD8td)。Windows x64 / CUDA12.8，完整包约 2.44 GiB。
- **5.0 beta（历史测试版）**：[历史版本与下载](https://github.com/ysuhao/Mintaria/releases/tag/v5.0.0-beta)。

GitHub 的5.1安装包分为五个分卷，Google Drive 分为27个分卷。选择一个平台，下载该平台的全部分卷与 `Merge-Mintaria.cmd`，放在同一新文件夹后运行合并脚本；两个平台的分卷请勿混用。夸克可直接下载完整EXE。

完整解压到新的空文件夹，运行 `MintVC/MintVC.exe`。无需安装Python，请保留旧目录；`Source code.zip`不是可运行客户端。

5.1正式版只在手动开始变声时选择缓冲档位，运行中保持固定；设备自动重连沿用原设置。保留后台普通程序优先级优化和积压跳过。更新登录、注册界面和Mintaria M图标，音色质量设置保持原样。

默认附带免费音色风妈，其他音色单独下载。普通`.pth`仍兼容，受保护的`.mintpth`需要账号登录及授权。持续算力不足时仍可能断音或跳过音频。

## 版本列表

| 版本 | 类型 | 发布说明 |
| --- | --- | --- |
| [v5.1.0](https://github.com/ysuhao/Mintaria/releases/tag/v5.1.0) | 正式版 | Mintaria 5.1 正式版 |
| [v5.0.0-beta](https://github.com/ysuhao/Mintaria/releases/tag/v5.0.0-beta) | 测试版 | Mintaria 5.0 beta |
| [v2.1.0](https://github.com/ysuhao/Mintaria/releases/tag/v2.1.0) | 正式版 | 萌妹AI变声（MintVC） · 2.1 |
| [v2.0.0](https://github.com/ysuhao/Mintaria/releases/tag/v2.0.0) | 正式版 | 萌妹AI变声（MintVC） · 2.0 |
| [v1.2.0](https://github.com/ysuhao/Mintaria/releases/tag/v1.2.0) | 正式版 | MintVCver1.0 · v1.2.0（音色展示与更新版） |
| [v1.1.0](https://github.com/ysuhao/Mintaria/releases/tag/v1.1.0) | 正式版 | MintVCver1.0 · v1.1.0（音质优化版） |
| [v1.0.4](https://github.com/ysuhao/Mintaria/releases/tag/v1.0.4) | 正式版 | MintVCver1.0 · v1.0.4（音质优化版） |
| [v1.0.3](https://github.com/ysuhao/Mintaria/releases/tag/v1.0.3) | 正式版 | MintVCver1.0 · v1.0.3（音质优化版） |
| [v1.0.2](https://github.com/ysuhao/Mintaria/releases/tag/v1.0.2) | 正式版 | MintVCver1.0 · v1.0.2（音质优化版） |
| [v1.0.1](https://github.com/ysuhao/Mintaria/releases/tag/v1.0.1) | 正式版 | MintVCver1.0 · v1.0.1（音质优化版） |
| [v1.0.0](https://github.com/ysuhao/Mintaria/releases/tag/v1.0.0) | 正式版 | MintVCver1.0 |

测试版单独标记为 Pre-release，后续更新继续发布在同一仓库。GitHub 的 Latest 指向最新正式发行版，因此目前仍为 2.1；需要 5.0 beta 请使用上面的测试版入口。

## 旧链接与旧客户端

原 `ysuhao/MintVC` 网页地址由 GitHub 跳转到本项目。部分旧客户端会严格校验旧仓库的更新元数据路径，改名后可能忽略更新信息；遇到这种情况，请从本页或官网下载完整包。5.0 beta 未发布自动更新。

## 使用与许可

建议使用耳机，通过虚拟声卡连接游戏或通话软件。不同音色、设备与游戏的实际效果可能不同。第三方组件的许可与署名见安装包内 notices。

作者：MINT RYU · [mintryu.com](https://mintryu.com/) · me@mintryu.com
