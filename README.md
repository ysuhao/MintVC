# MintVCver1.0

Windows 本机实时 RVC 变声客户端 · MINT RYU

## 下载

请到 [最新版本下载页](https://github.com/ysuhao/MintVC/releases/latest) 下载软件包。
不要下载 GitHub 自动生成的 Source code.zip，它不是软件运行包。

完整解压后运行 `MintVCver1.0.exe`，点击“进入”，载入你自己有权使用的 `.pth` 音色并选择输入/输出设备。
运行包包含本机 Python/RVC/FCPE/RNNoise 依赖，不需要安装 Python 或连接 VPS；不包含私人音色、账号数据、虚拟声卡驱动。

- Windows 10/11 x64；此版本的 GPU 加速面向 NVIDIA CUDA 11.8 兼容显卡，其他硬件未经实机验证。
- 默认 FCPE / 100ms 处理块，MME 和 WASAPI 设备。
- 本机降噪、空间效果；齿轮菜单不会暂停实时音频线程。
- 高级设置中的游戏优化可关闭，目标上限 120 FPS（受驱动和游戏支持限制）。

首次启动未签名程序时 Windows 可能提示 SmartScreen；请核对 SHA-256，不要关闭系统安全防护。
第三方许可证包含在运行包内。作者主页：[mintryu.com](https://mintryu.com/)。
