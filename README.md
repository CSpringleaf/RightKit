# RightKit

轻量的 macOS Finder 原生右键菜单工具。

- 新建 TXT、Markdown、Word、Excel、PowerPoint 文件。
- 复制文件或文件夹路径，在 Terminal 中打开当前文件夹。
- 顶部菜单栏查看运行状态、管理权限和检查更新。

**[下载最新版](https://github.com/CSpringleaf/RightKit/releases/latest)**

支持 Apple Silicon（M 系列）Mac，macOS 13 或更高版本。暂不支持 Intel Mac。

## 安装

1. 下载 Releases 中的 `.dmg`，将 RightKit 拖到“应用程序”。
2. 推出安装磁盘，从“应用程序”中打开 RightKit。
3. 按应用引导启用 Finder 扩展；需要父菜单点击保护时再开启辅助功能权限。

当前为 ad-hoc 签名测试分发版，尚未完成 Developer ID 签名和 Apple 公证。
首次打开可能遇到 macOS 安全提示，可参照 [Apple 官方说明](https://support.apple.com/102445) 处理可信应用的打开提示。

## 更新

1.4.0 开始支持应用内更新。顶部菜单栏点击“检查更新”，确认后下载安装并重启。
默认每天自动检查一次，可关闭；后台发现新版会在菜单栏图标旁显示圆点。
更新清单和安装包均校验 EdDSA 签名。

1.3.0 及更早版本需要先手动安装一次 1.4.0 或更新版本。
由于测试版使用临时签名，升级后辅助功能保护可能需要重新授权。

此仓库用于安装包、更新清单与使用说明的发布，不包含应用源码。
第三方组件与许可随应用提供：Sparkle 更新框架，以及 MacRightClick 的 Office 模板。
