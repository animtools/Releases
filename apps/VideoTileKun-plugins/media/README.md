# メディア（デモ・スクリーンショット）

このフォルダにデモ用の **GIF** や画像を置くと、README や GitHub Release の説明文から参照できます。

## 使い方

### README で表示する

`apps/VideoTileKun-plugins/README.md` の「デモ・スクリーンショット」セクションで、次のように相対パスで指定します。

```markdown
![タイル一覧](media/tile-grid.gif)
![ホバープレビュー](media/hover-preview.gif)
```

### GitHub Release の説明文で使う

1. GIF をこのフォルダに置き、リポジトリに push する。
2. Release の「Describe」欄に、**raw URL** で画像を埋め込みます。

Markdown の例:

```markdown
## デモ

![タイル一覧](https://github.com/animtools/Releases/raw/main/apps/VideoTileKun-plugins/media/tile-grid.gif)
```

URL 形式: `https://github.com/animtools/Releases/raw/main/apps/VideoTileKun-plugins/media/ファイル名.gif`

### 推奨ファイル名（例）

- `tile-grid.gif` — タイルグリッド一覧
- `hover-preview.gif` — ホバーでプレビュー再生
- `inspector-tile.gif` — Inspector のタイル表示
- `player-timeline.gif` — Player のタイムライン
