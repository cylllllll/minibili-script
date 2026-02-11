# 📺 Bilibili to MiniBili Redirector

**Bilibili Web to MiniBili** 是一个脚本旨在提升 iOS 用户在 Bilibili 的浏览体验。

它会自动检测你在浏览器中访问的 Bilibili 视频页面或搜索页面，并将它们无缝重定向到本地安装的 **MiniBili** 中打开，让你享受原生应用的流畅播放体验，告别网页版的繁杂干扰。

## ✨ 功能特性

* **视频重定向**: 当访问 `m.bilibili.com/video/BV...` 链接时，自动唤起 MiniBili 播放。
* **搜索重定向**: 当访问 `search.bilibili.com` 进行搜索时，自动将搜索词传递给 MiniBili 进行搜索。
* **无感跳转**: 脚本运行迅速，尽量减少网页加载时间。
* **防误触机制**: (可选功能，视你脚本逻辑而定) 提供页面上的按钮手动跳转，而非强制自动跳转。

## 🛠 前置要求

在安装此脚本之前，请确保你已经安装了以下软件：

1. **MiniBili App**: 必须安装在你的 iOS 设备上。


2. **支持的App**:
* [Surge](https://raw.githubusercontent.com/cylllllll/minibili-script/refs/heads/main/MiniBili.sgmodule) 
* [Loon](https://raw.githubusercontent.com/cylllllll/minibili-script/refs/heads/main/MiniBili.plugin) 
* [Stash](https://raw.githubusercontent.com/cylllllll/minibili-script/refs/heads/main/MiniBili.stoverride)
* [Quantumult X](https://raw.githubusercontent.com/cylllllll/minibili-script/refs/heads/main/MiniBili.snippet) 


## 📖 使用说明

脚本安装并启用后，无需额外配置即可工作：

1. **打开视频**: 在浏览器地址栏输入或点击任意 Bilibili 视频链接。
2. **唤醒提示**: 浏览器可能会弹出一个确认框：“是否允许打开 MiniBili？”。
* 建议勾选 **"始终允许 (Always allow...)"**，这样以后就会自动跳转，不再询问。


3. **观看**: 视频将直接在 MiniBili 客户端中开始播放。

## 🔧 支持的 URL 类型

目前脚本支持以下类型的链接重定向：

| 类型 | 网页 URL 示例 | MiniBili 行为 |
| --- | --- | --- |
| **普通视频** | `https://m.bilibili.com/video/BV1xx...` | 打开对应视频详情/播放页 |
| **搜索页面** | `https://search.bilibili.com/all?keyword=...` | 打开 App 并搜索对应关键词 |


## 📄 许可证 (License)

本项目基于 [MIT License](https://www.google.com/search?q=./LICENSE) 开源。

---



**Disclaimer / 免责声明**:
本项目与 Bilibili (哔哩哔哩) 官方及 MiniBili 无任何关联。脚本仅作为用户工具，用于提升个人浏览体验。使用本脚本所产生的任何后果由用户自行承担。
