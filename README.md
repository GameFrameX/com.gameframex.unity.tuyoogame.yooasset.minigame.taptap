<div align="center">

<img src="https://download.alianblank.com/gameframex/gameframex_logo_320.png" alt="Game Frame X Logo" width="160" />

# GameFrameX YooAsset MiniGame TapTap

[![License](https://img.shields.io/github/license/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.taptap)](https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.taptap/blob/main/LICENSE.md)
[![Version](https://img.shields.io/github/v/release/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.taptap)](https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.taptap/releases)
[![Unity Version](https://img.shields.io/badge/Unity-2019.4-black?logo=unity)](https://unity.com/)
[![Documentation](https://img.shields.io/badge/Documentation-docs-blue)](https://gameframex.doc.alianblank.com)

All-in-One Solution for Indie Game Development · Empowering Indie Developers' Dreams

<br />

[Documentation](https://gameframex.doc.alianblank.com) · [Quick Start](#quick-start) · QQ Group: 467608841 / 233840761

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

### Installation

Choose one of the following methods:

1. Edit your Unity project's `Packages/manifest.json` and add the `scopedRegistries` section:
   ```json
   {
     "scopedRegistries": [
       {
         "name": "GameFrameX",
         "url": "https://gameframex.upm.alianblank.uk",
         "scopes": [
           "com.gameframex"
         ]
       }
     ],
     "dependencies": {
       "com.gameframex.unity.tuyoogame.yooasset.minigame.taptap": "1.0.0"
     }
   }
   ```

   `scopes` controls which packages are resolved through this registry. Only packages whose names start with `com.gameframex` will be fetched from it.

2. Add to `manifest.json` dependencies:
   ```json
   {
      "com.gameframex.unity.tuyoogame.yooasset.minigame.taptap": "https://github.com/gameframex/com.gameframex.unity.tuyoogame.yooasset.minigame.taptap.git"
   }
   ```
3. Use **Package Manager** in Unity with **Git URL**: `https://github.com/gameframex/com.gameframex.unity.tuyoogame.yooasset.minigame.taptap.git`
4. Clone the repository into your Unity project's `Packages` directory. It will be loaded automatically.
## Documentation & Resources

- [Official Documentation](https://gameframex.doc.alianblank.com)

## Community & Support

- QQ Group: [Join](https://qm.qq.com/q/3dIpogITg)

## Changelog

See [Releases](https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.taptap/releases) for changelog.


## Dependencies

| Package | Description |
|---------|-------------|
| `com.gameframex.unity.tuyoogame.yooasset` | 1.0.0 |
## License

See [LICENSE.md](LICENSE.md) for license information.
