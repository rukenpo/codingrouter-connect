# CodingRouter Connect

CodingRouter 桌面客户端，基于 [CC Switch](https://github.com/farion1231/cc-switch) 二次开发，提供 AI 编程工具快速配置、账户与令牌管理，以及钱包入口。

**[查看版本与下载安装包](https://github.com/rukenpo/codingrouter-connect/releases)** · **[CodingRouter](https://api.codingrouter.ai)**

本仓库仅用于发布安装包、版本说明和更新元数据，不托管应用源码。[v0.1.1 已发布](https://github.com/rukenpo/codingrouter-connect/releases/tag/v0.1.1)，提供完整 19 个发布文件；macOS 版本已完成 Apple 签名与公证。

## 平台与下载格式

发版目标与 CC Switch 官方对齐；每个版本的实际构建、签名和验证状态以 Release 说明为准。

| 平台 | 架构 | 手动安装 |
| --- | --- | --- |
| macOS 12+ | Universal：Intel 与 Apple Silicon | `.dmg` 或 `.zip` |
| Windows 10+ | x64 | `.msi` 或 `Portable.zip` |
| Windows on ARM | ARM64 | `arm64.msi` 或 `arm64-Portable.zip` |
| Linux | x64 / ARM64 | `.AppImage`、`.deb`、`.rpm` |

Linux 需要 glibc 2.35+ 与 WebKitGTK 4.1。更新资产另包含 macOS `.tar.gz`、五个 `.sig` 和六个平台键的 `latest.json`，完整版本共 19 个上传资产。GitHub 自动生成的 Source code 下载仅包含本仓库说明文件，不是应用源码。

## 发布状态

带有 **Pre-release** 标识的版本用于测试。请阅读对应版本的已知限制；未完成 Apple Developer ID 签名和公证的版本会明确标注，不将其描述为已公证。当前客户端检查正式版本后打开 Release 页，由用户选择安装包，不自动覆盖安装。

## 开源致谢

CodingRouter Connect 基于 CC Switch 二次开发，感谢原作者及社区贡献者。

**CC Switch — Copyright (c) 2025 Jason Young — MIT License**

原项目版权及许可保留在客户端 About 页面和本仓库的 [MIT 许可证](LICENSE-CC-Switch.txt)。CodingRouter Connect 为独立衍生项目，并非 CC Switch 官方发行版。
