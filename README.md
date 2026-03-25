# Kazumi Android 32-bit 镜像仓库

本仓库用于自动构建并提供基于上游 [Predidit/Kazumi](https://github.com/Predidit/Kazumi) 的 **Android 32 位（`armeabi-v7a`）APK**。

> [!IMPORTANT]
> 本仓库并非官方仓库，仅用于提供 **Android 32 位兼容版本**。
>
> 由于本仓库无法获取上游私有的 GitHub Actions secrets（例如 `DANDANAPI_APPID`、`DANDANAPI_KEY`），因此部分依赖 DanDan API / 弹弹Play 的功能可能不可用，包括但不限于：
>
> - 无法正常获取弹弹Play弹幕
> - 弹幕功能缺失
> - DanDan API 相关功能不可用或异常
>
> 如需完整功能，请优先使用上游官方版本：  
> https://github.com/Predidit/Kazumi

## 上游项目

- 上游仓库： https://github.com/Predidit/Kazumi
- 官方发布： https://github.com/Predidit/Kazumi/releases

## 本仓库说明

- 自动跟踪上游 release
- 自动构建 **Android 32 位 APK**
- 仅用于兼容 32 位设备
- 不保证与官方版本功能完全一致

## 下载

请前往本仓库的 Releases 页面下载最新 APK。

## 声明

原项目版权、代码与维护归属于上游项目作者及贡献者。  
本仓库仅为社区兼容性构建与分发用途。
