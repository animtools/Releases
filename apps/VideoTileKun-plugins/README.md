# Eagle プラグインセット（Video Tile-kun）

[Eagle](https://en.eagle.cool/) 用の **Video Tile-kun** 系プラグイン 3 本をひとまとまりにした配布です。動画のタイル（サムネイル）表示・プレーヤー・自動タイル生成をサポートします。

---

## 含まれるプラグイン

| プラグイン | 役割 |
|------------|------|
| **VideoTileKunInspector** | インスペクタで動画のタイル（サムネイル）を生成・表示。ホバーでプレビュー再生。 |
| **VideoTileKunPlayer** | 動画専用プレーヤー。タイムライン・マーカー・タイルビュー付き。 |
| **VideoTileKunService** | 動画をライブラリに追加したときに、バックグラウンドでタイルを自動生成。 |

3 本とも連携して使うことを想定していますが、必要なものだけ入れても動作します。

---

## ダウンロード

[Releases](https://github.com/animtools/Releases/releases) から最新の **VideoTileKun-plugins-vX.Y.Z.zip**（または同梱の各プラグイン zip）を取得し、Eagle のプラグインフォルダに配置してください。

**VirusTotal**: スキャン結果は各 [リリースページの説明欄](https://github.com/animtools/Releases/releases) に掲載しています。

※ X.Y.Z はバージョン番号です。リリースによっては「VideoTileKun-plugins」という名前の zip 1 本、またはプラグイン別の zip が含まれる場合があります。

---

## ドキュメント（このセット）

- **[QUICKSTART.md](./QUICKSTART.md)** — 最短の入れ方（ダウンロード〜Eagle にインストール〜初回の流れ）
- **[USER_GUIDE.md](./USER_GUIDE.md)** — 各プラグインの役割と基本的な使い方
- **[CHANGELOG.md](./CHANGELOG.md)** — バージョンごとの変更内容

---

## 動作環境

- **Eagle** 4.0 以降
- **VideoTileKunInspector / VideoTileKunService**: FFmpeg プラグイン（Eagle のプラグイン設定からインストール）が必要です。
- **VideoTileKunPlayer**: 追加のプラグインは不要です。

---

## サポート

不具合報告・質問はリポジトリ共通の窓口をご利用ください。  
→ [../../SUPPORT.md](../../SUPPORT.md)（ルートの SUPPORT.md）

報告時は対象プラグイン名（例: VideoTileKunInspector）を明記していただけると助かります。
