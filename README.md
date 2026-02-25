# リリース配布リポジトリ

このリポジトリでは、同一プロジェクトで開発している複数アプリの**配布用バイナリ**を GitHub Releases で公開しています。ソースコードは別リポジトリで管理しています。

**LAG 公式サイト（ドキュメント）**:
- **トップ**: [LAG | The Lazy Animator's Garage](https://lag-site.vercel.app/)
- **VideoTileKun プラグイン**（概要・Inspector・Player・Service）: [ドキュメント](https://lag-site.vercel.app/docs.html#vtk-overview)
- **VideoTileKun Desktop 版**: [ドキュメント](https://lag-site.vercel.app/desktop-docs.html)

**このリポジトリ内のドキュメント**: 各アプリの説明・使い方・変更履歴は **`apps/アプリ名/`** にまとまっています。下記の「アプリのドキュメント」リンクからご覧ください。

**VirusTotal**: 最新版・過去版のスキャン結果は、各 [Releases](https://github.com/animtools/Releases/releases) の説明欄をご確認ください。リンクはリリースごとの説明にのみ掲載しています。

---

## 公開アプリ一覧

### VideoTileKun-desktop（デスクトップアプリ）

動画のタイルプレビュー・ライブラリ管理ができる Windows 用デスクトップアプリ（Electron・ポータブル版）です。

- **ダウンロード**: [Releases](https://github.com/animtools/Releases/releases) から最新の **VideoTileKun-desktop-vX.Y.Z-win64.zip** を取得し、解凍して付属の exe を起動してください。
- **公式ドキュメント（このアプリ）**: [apps/VideoTileKun-desktop/](./apps/VideoTileKun-desktop/)  
  - [README（説明・機能・動作環境）](./apps/VideoTileKun-desktop/README.md)  
  - [ユーザーガイド](./apps/VideoTileKun-desktop/USER_GUIDE.md)  
  - [クイックスタート](./apps/VideoTileKun-desktop/QUICKSTART.md)  
  - [変更履歴（CHANGELOG）](./apps/VideoTileKun-desktop/CHANGELOG.md)

### VideoTileKun-plugins（Eagle プラグインセット）

Eagle 用の VideoTileKun 系プラグイン 3 本（Inspector / Player / Service）をひとまとまりにした配布です。

- **ダウンロード**: [Releases](https://github.com/animtools/Releases/releases) から最新の **VideoTileKun-plugins-vX.Y.Z.zip** を取得し、Eagle のプラグインフォルダに配置してください。
- **公式ドキュメント（このセット）**: [apps/VideoTileKun-plugins/](./apps/VideoTileKun-plugins/)  
  - [README（概要・含まれるプラグイン）](./apps/VideoTileKun-plugins/README.md)  
  - [ユーザーガイド](./apps/VideoTileKun-plugins/USER_GUIDE.md)  
  - [クイックスタート](./apps/VideoTileKun-plugins/QUICKSTART.md)  
  - [変更履歴（CHANGELOG）](./apps/VideoTileKun-plugins/CHANGELOG.md)

---

## サポート

不具合報告・質問・要望は **リポジトリ共通の窓口** をご利用ください。

→ **[SUPPORT.md](./SUPPORT.md)**（報告の仕方・FAQ）

---

## ライセンス

各アプリは **再配布可・改変禁止** の利用条件です。未改変のままの再配布は可能で、改変・派生作品の作成・配布はできません。詳細は [LICENSE](./LICENSE) を参照してください。
