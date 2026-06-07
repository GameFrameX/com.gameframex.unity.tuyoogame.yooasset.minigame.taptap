<div align="center">

<img src="https://download.alianblank.com/gameframex/gameframex_logo_320.png" alt="Game Frame X Logo" width="160" />

# GameFrameX YooAsset MiniGame TapTap

[![License](https://img.shields.io/github/license/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.taptap)](https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.taptap/blob/main/LICENSE.md)
[![Version](https://img.shields.io/github/v/release/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.taptap)](https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.taptap/releases)
[![Unity Version](https://img.shields.io/badge/Unity-2019.4-black?logo=unity)](https://unity.com/)
[![Documentation](https://img.shields.io/badge/Documentation-docs-blue)](https://gameframex.doc.alianblank.com)

インディゲーム開発者向けオールインワンソリューション · インディ開発者の夢を支援

<br />

[ドキュメント](https://gameframex.doc.alianblank.com) · [クイックスタート](#クイックスタート) · QQグループ: 467608841 / 233840761

<br />

[English](README.md) | [简体中文](README.zh-CN.md) | [繁體中文](README.zh-TW.md) | **日本語** | [한국어](README.ko.md)

</div>

## プロジェクト概要

GameFrameX の YooAsset TapTap ミニゲームランタイムコンポーネント。Unity WebGL プラットフォーム向けに、TapTap ミニゲームのファイルシステムとアセットバンドル読み込みフローの適配実装を提供します。

## 機能

- TapTap ミニゲーム専用の IFileSystem 実装を提供
- TapTap ミニゲーム SDK の AssetBundle ダウンロードとキャッシュワークフローに適配
- パッケージバージョンリクエスト、マニフェスト読み込み、アセットバンドルダウンロードと読み込みをサポート
- リモートサービスと復号サービスに対応

## 動作環境

- Unity 2019.4
- プラットフォーム：UNITY_WEBGL
- 条件付きコンパイル：TAPTAPMINIGAME
- 依存関係：YooAsset、StarkWebGL、TapTapWebGL

## クイックスタート

### インストール

以下のいずれかの方法を選択してください：

1. Unity プロジェクトの `Packages/manifest.json` を編集し、`scopedRegistries` セクションを追加してください：
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

   `scopes` は、どのパッケージをこのレジストリから解決するかを制御します。`com.gameframex` で始まるパッケージのみがこのレジストリから取得されます。

2. `manifest.json` の `dependencies` に直接追加：
   ```json
   {
      "com.gameframex.unity.tuyoogame.yooasset.minigame.taptap": "https://github.com/gameframex/com.gameframex.unity.tuyoogame.yooasset.minigame.taptap.git"
   }
   ```
3. Unity の **Package Manager** で **Git URL** を使用して追加：`https://github.com/gameframex/com.gameframex.unity.tuyoogame.yooasset.minigame.taptap.git`
4. リポジトリを Unity プロジェクトの `Packages` ディレクトリにクローンしてください。自動的に読み込まれます。
## ドキュメントとリソース

- [公式ドキュメント](https://gameframex.doc.alianblank.com)

## コミュニティとサポート

- QQグループ: [参加](https://qm.qq.com/q/3dIpogITg)

## 変更履歴

変更履歴は [Releases](https://github.com/GameFrameX/com.gameframex.unity.tuyoogame.yooasset.minigame.taptap/releases) をご覧ください。


## 依存関係

| パッケージ | 説明 |
|----------|------|
| `com.gameframex.unity.tuyoogame.yooasset` | 1.0.0 |
## ライセンス

詳しくは [LICENSE.md](LICENSE.md) をご参照ください。
