> ⚠️ **非官方个人构建 | Unofficial Personal Build**
> 
> 本仓库是 [MobileGL-Dev/MobileGL](https://github.com/MobileGL-Dev/MobileGL) 的 Fork，构建产物为个人预先编译版，**非官方发行正式版**。如有问题请勿向原项目提交 Issue。
> 
> This is an unofficial personal build. **NOT an official release.** Do NOT report issues to the upstream project.

---

# MGL (MobileGL) Android Builds

[中文](#中文) | [English](#english)

---

## 中文

本仓库通过 GitHub Actions 云编译 Android 版 MobileGL 渲染器插件 APK。

### MobileGL 是什么

MobileGL（简称 MGL）是新一代 Minecraft Java 版安卓渲染引擎，由 MobileGlues 团队开发。相比上一代 MG 渲染器（MobileGlues），MGL 采用全新多后端架构：

- **DirectVulkan (Magma)**：基于 Vulkan，高性能，推荐骁龙 8 系列机型
- **DirectGLES (Espryt)**：基于 OpenGL ES，兼容性更广

目前 MGL 仍在开发中，目标 OpenGL 3.3 Core Profile，**暂无官方正式版**。

### 下载

前往 [Releases](../../releases) 下载最新的 APK。

### 使用方法

1. 安装 APK
2. 打开 ZL2 / Zalith Launcher / FoldCraft Launcher
3. 渲染器设置 → 选择 **MobileGL**
4. 后端选择：`DirectVulkan`（性能优先）或 `DirectGLES`（兼容优先）
5. 进入游戏，F3 调试屏幕确认渲染器显示 `MobileGL`

### 自行构建

Fork 本仓库 → Actions → Build MGL → Run workflow。详见 `.github/workflows/build-mgl.yml`。

### 致谢

- [MobileGL-Dev](https://github.com/MobileGL-Dev) — 原项目团队
- [ZalithLauncher](https://github.com/ZalithLauncher) — 启动器渲染器插件规范

---

## English

This is a fork for cloud-building Android renderer plugin APKs via GitHub Actions.

### What is MobileGL

MobileGL (MGL) is a next-gen OpenGL rendering engine for Minecraft Java Edition on Android. Built by the MobileGlues team, it features a multi-backend architecture:

- **DirectVulkan (Magma)** — Vulkan-based, high performance (Snapdragon 8 series recommended)
- **DirectGLES (Espryt)** — OpenGL ES-based, broader compatibility

MGL targets OpenGL 3.3 Core Profile and is under active development. **No official release yet.**

### Download

Get the latest APK from [Releases](../../releases).

### Usage

1. Install the APK
2. Open ZL2 / Zalith Launcher / FoldCraft Launcher
3. Renderer settings → select **MobileGL**
4. Choose backend: `DirectVulkan` (performance) or `DirectGLES` (compatibility)
5. Launch the game and check F3 debug screen for `MobileGL`

### Build it yourself

Fork → Actions → Build MGL → Run workflow. See `.github/workflows/build-mgl.yml`.

### Credits

- [MobileGL-Dev](https://github.com/MobileGL-Dev) — original project
- [ZalithLauncher](https://github.com/ZalithLauncher) — renderer plugin spec
