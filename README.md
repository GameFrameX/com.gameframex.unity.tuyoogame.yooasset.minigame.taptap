<div align="center">

<img src="https://download.alianblank.com/gameframex/gameframex_logo_320.png" alt="Game Frame X Logo" width="160" />

# GameFrameX YooAsset MiniGame TapTap

[![License](https://img.shields.io/github/license/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.taptap)](https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.taptap/blob/main/LICENSE.md)
[![Version](https://img.shields.io/github/v/release/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.taptap)](https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.taptap/releases)
[![Documentation](https://img.shields.io/badge/Documentation-docs-blue)](https://gameframex.doc.alianblank.com)

All-in-One Solution for Indie Game Development · Empowering Indie Developers' Dreams

<br />

[Documentation](https://gameframex.doc.alianblank.com) · [Quick Start](#quick-start) · [QQ Group](https://qm.qq.com/q/3dIpogITg)

<br />

**English** | [简体中文](README.zh-CN.md) | [繁體中文](README.zh-TW.md) | [日本語](README.ja.md) | [한국어](README.ko.md)

</div>
## Project Overview

GameFrameX YooAsset MiniGame TapTap runtime component for Unity WebGL platform. Provides adapter implementation for TapTap Mini Game file system and asset bundle loading.

## Features

- Provides TapTap Mini Game specific IFileSystem implementation
- Adapts TapTap Mini Game SDK's AssetBundle download and caching workflow
- Supports package version requests, manifest loading, asset bundle download and loading
- Compatible with remote services and decryption services

## Requirements

- Unity 2019.4
- Platform: UNITY_WEBGL
- Conditional compilation: TAPTAPMINIGAME
- Dependencies: YooAsset, StarkWebGL, TapTapWebGL

## Quick Start

### Installation (choose one)

1. Add the following to the `dependencies` section of your `manifest.json`:
   ```json
   {"com.gameframex.unity.tuyoogame.yooasset.minigame.taptap": "https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.taptap.git"}
   ```

2. In Unity's Package Manager, use `Git URL` to add the package: https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.taptap.git

3. Download the repository and place it in your Unity project's `Packages` directory. It will be loaded automatically.

### Usage

1. Ensure TapTap Mini Game SDK is integrated and `TAPTAPMINIGAME` macro is enabled
2. Use `TapTapFileSystemCreater.CreateFileSystemParameters(...)` to generate file system parameters
3. Pass the parameters to YooAsset's file system creation workflow
4. Follow YooAsset's standard workflow for initialization, version requests, manifest loading, and asset loading

## Documentation & Resources

- [Official Documentation](https://gameframex.doc.alianblank.com)

## Community & Support

- QQ Group: [Join](https://qm.qq.com/q/3dIpogITg)

## Changelog

See [Releases](https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.taptap/releases) for changelog.

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.taptap/blob/main/LICENSE) file for details.
