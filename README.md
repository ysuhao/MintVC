# Mintaria · 萌音

Windows 实时 AI 变声，声音在本机处理。原项目名称为 MintVC / 萌妹AI变声。

[官网与音色库](https://mintaria.mintryu.com/) · [全部版本与更新记录](https://github.com/ysuhao/Mintaria/releases)

## 一个项目，持续更新

所有历史版本和后续更新统一发布在本仓库的 **Releases** 中。点击页面右上角 **Star** 即可收藏整个 Mintaria 项目，无需为每个版本重复收藏。需要更新通知可选择 **Watch → Custom → Releases**。

本公开仓库提供产品介绍、更新记录与安装包下载。

## 当前下载

- **Mintaria 5.1.1 正式版**：[GitHub 分卷下载](https://github.com/ysuhao/Mintaria/releases/tag/v5.1.1) · [夸克完整包](https://pan.quark.cn/s/a40d958dba18) · [Google Drive 下载](https://drive.google.com/open?id=1flIWqPIXaEHQbYO4U7bGVTjYSfTUg66f)。Windows x64 / CUDA12.8，完整包约 2.61 GiB。
- **5.1 正式版（历史版本）**：[v5.1.0](https://github.com/ysuhao/Mintaria/releases/tag/v5.1.0)。
- **5.0 beta（历史测试版）**：[历史版本与下载](https://github.com/ysuhao/Mintaria/releases/tag/v5.0.0-beta)。

GitHub 的 5.1.1 安装包分为 6 个分卷，下载全部分卷与 `Merge-Mintaria.cmd`，放在同一新文件夹后运行合并脚本。夸克与 Google Drive 可下载完整 EXE。

完整解压到新的空文件夹，运行 `MintVC/MintVC.exe`。无需安装 Python，请保留旧目录；`Source code.zip` 不是可运行客户端。

5.1.1 减少显卡同步等待，为音频收发与推理线程增加 MMCSS 调度保护，并在会话期间退出本进程电源节流。自适应缓冲在1000ms年龄硬上限内吸收迟到，仅在安静片段回收延迟；关闭自适应时保留固定时限。已完成数值一致性、资源恢复和延迟尖峰仿真，尚未完成新版真实对局听感验收。

默认附带免费音色风妈，其他音色单独下载。普通 `.pth` 仍兼容，受保护的 `.mintpth` 需要账号登录及授权。持续算力不足或极端系统抢占时仍可能断音或跳过音频。

## 版本列表

| 版本 | 类型 | 发布说明 |
| --- | --- | --- |
| [v5.1.1](https://github.com/ysuhao/Mintaria/releases/tag/v5.1.1) | 正式版 | Mintaria 5.1.1 正式版 |
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
