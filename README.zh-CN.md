<div align="center">

# Klaruvo

[English](README.md) · **简体中文**

**本地运行的 AI 图片处理工具 —— 批量处理 · 自媒体封面图 · 图片文字移位 · 去水印 · 抠图 · 扩图 · 放大**

图片不出本机、离线可用、无广告、无水印。

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20macOS-lightgrey)](#-下载安装)
[![Latest Release](https://img.shields.io/github/v/release/powersoftware-app/Klaruvo?label=最新版本)](https://github.com/powersoftware-app/Klaruvo/releases/latest)

[下载安装包](#-下载安装) · [功能特性](#-功能特性) · [常见问题](#-常见问题) · [产品详情 / 购买授权](https://www.powersoftware.app/product/detail/klaruvo)

</div>

---

## ✨ 功能特性

> **三大重点能力：批量处理 · 自媒体封面图 · 图片文字移位**

| 能力 | 说明 |
| --- | --- |
| 📦 **批量处理** | 选一个纯图片文件夹，按统一参数一次性处理完，结果打包成 zip 下载 |
| 🖼 **自媒体封面图** | 填一次标题 / 副标题，按 18 种平台规格（小红书、抖音、B站、公众号、YouTube、Instagram、Facebook、LinkedIn…）一次出图，多规格打包下载 |
| ↔️ **图片文字移位** | 把画面里的文字、贴纸、物体直接拖到新位置，原位置自动填充修复；「文字模式」只搬运同色文字笔画，不误伤背景 |
| 🧹 **去水印 / 去杂物** | 涂抹即清，AI 自动补全背景 |
| 🖌 **智能点选清除** | 点一下选中目标再清除，无需精细涂抹 |
| ✂️ **一键抠图** | 自动分离主体与背景，输出透明底或指定底色 |
| 🔍 **图片放大** | 超分辨率放大，提升清晰度与细节 |
| 😊 **人脸修复** | 老照片 / 模糊人脸修复增强，黑白照片可自动上色 |
| 🪪 **证件照** | 一键裁切标准证件照尺寸并更换底色 |
| 🔄 **换背景** | 证件照 / 商品图 / 人像三种模式，纯色或自定义背景图 |
| 🖼 **AI 扩图 / 重画** | 扩展画面、按提示重绘局部 |
| 🌐 **中英双语界面** | 右上角【中 / EN】一键切换 |
| 🔒 **本地运行** | 图片不上传云端，首次下载模型后离线可用 |

**批量处理支持的功能**（一次处理整个文件夹）：

`去水印` · `放大` · `抠图换底色` · `人脸修复` · `老照片上色` · `换背景` · `证件照` · `自媒体封面`

**本软件面向普通用户的核心增强：**

- **一键启动器**：图形界面自动检测 / 安装运行环境 → 下载模型 → 启动服务 → 打开浏览器，零命令行基础可用
- **下载体系强化**：多源测速选优（官方源 / 自建镜像 / 公益镜像），分片并行、断点续传、慢源自动切换，国内网络也能顺利下载
- **多套硬件配置预设**：从低配纯 CPU 到高配独显全覆盖，启动器按机器配置自动推荐
- **批量处理**：整目录批量去水印 / 抠图 / 放大 / 换背景，统一参数、一键打包

## 📸 界面预览

| 一键启动器 | 主界面 |
| --- | --- |
| ![launcher](images/launcher.png) | ![screenshot](images/screenshot.png) |

## 🚀 下载安装

前往 **[Releases](https://github.com/powersoftware-app/Klaruvo/releases)** 页面下载对应平台产物：

| 平台 | 产物 | 用法 |
| --- | --- | --- |
| Windows | `Klaruvo-Setup.exe` | 双击安装 → 桌面快捷方式启动，首次使用自动下载运行环境 |
| macOS | `Klaruvo-mac-<arch>.dmg` | 打开 DMG，拖入 Applications；首次运行请右键 → 打开（绕过 Gatekeeper） |

> 安装包体积很小：运行环境与模型在**首次使用时自动联网下载**，之后完全离线。
> 启动器会自动探测本机已有的运行环境，避免重复下载。

**环境要求**：Windows 10/11 或 macOS；建议磁盘预留 15GB 空间用于模型缓存；
NVIDIA 显卡可选用于加速（CPU 亦可运行）。

## ❓ 常见问题

| 问题 | 解决 |
| --- | --- |
| 端口被占用 | 在启动器中更换端口后重新启动 |
| 模型下载失败 | 启动器会自动多源重试；也可手动下载后放入模型目录 |
| 显存不足 | 在启动器中切换到更低档配置预设 |
| Windows 报 fbgemm.dll 错误 | PyTorch 已知问题，更换 PyTorch 版本可解决 |
| macOS 提示应用已损坏 / 无法打开 | 右键 → 打开；或在「系统设置 → 隐私与安全性」中放行 |

## 🛒 试用与授权

Klaruvo 首发于 **[幂栈网 PowerSoftware](https://www.powersoftware.app)** —— 面向独立开发者的软件分发与授权管理平台。

👉 **[查看 Klaruvo 产品详情 / 免费下载试用 / 购买授权](https://www.powersoftware.app/product/detail/klaruvo)**

- **先用后付**：0 元下载完整安装包，免费试用后再购买授权码解锁付费功能
- **自动发码**：支付成功后自动发放授权码并邮件送达，软件内一键激活
- **全球支付**：支付宝 / 微信 / PayPal / Waffo（信用卡、Apple Pay、Google Pay）

## 📄 许可与致谢

本软件基于开源项目 [IOPaint](https://github.com/Sanster/IOPaint) 二次开发。
分发的可执行文件以 [Apache-2.0](LICENSE) 授权；本仓库仅提供产品介绍与下载入口，
**不包含源代码**。详见 [LICENSE](LICENSE) 末尾的补充说明。

核心能力来自以下优秀开源项目：

[IOPaint](https://github.com/Sanster/IOPaint) · [LaMa](https://github.com/advimman/lama) · [SAM](https://github.com/facebookresearch/segment-anything) · [Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN) · [GFPGAN](https://github.com/TencentARC/GFPGAN) · [AnyText](https://github.com/tyxsspa/AnyText) · [PowerPaint](https://github.com/zhuang2002/PowerPaint)

---

<div align="center">

本仓库不接受 Issue 与 PR；使用问题请通过 **[幂栈网](https://www.powersoftware.app)** 反馈。

</div>
