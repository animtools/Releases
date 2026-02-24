# メディア（デモ・スクリーンショット）

このフォルダにデモ用の **GIF** や画像を置くと、README や GitHub Release の説明文から参照できます。

## 使い方

### README で表示する

`apps/VideoTileKun-desktop/README.md` の「デモ・スクリーンショット」セクションで、次のように相対パスで指定します。

```markdown
![タイル生成](media/tile-generation.gif)
![ライブラリ](media/library.gif)
```

### GitHub Release の説明文で使う

1. GIF をこのフォルダに置き、リポジトリに push する。
2. Release の「Describe」欄に、**raw URL** で画像を埋め込みます。

Markdown の例:

```markdown
## デモ

![タイル生成](https://github.com/animtools/Releases/raw/main/apps/VideoTileKun-desktop/media/tile-generation.gif)
```

URL 形式: `https://github.com/animtools/Releases/raw/main/apps/VideoTileKun-desktop/media/ファイル名.gif`

### 推奨ファイル名（例）

- `tile-generation.gif` — タイル生成の流れ
- `library.gif` — ライブラリウィンドウ・ドラッグ＆ドロップ
- `player-timeline.gif` — プレーヤーのタイムライン・マーカー
- `demo.gif` — 汎用デモ（1本だけ置く場合）
