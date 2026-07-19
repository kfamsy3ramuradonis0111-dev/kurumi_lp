# Kurumi Worldview LP

Vercelにそのままアップできる静的HTML形式です。

## 構成

- `index.html` : LP本体
- `assets/01.mp4` : 1ページ目動画
- `assets/02.mp4` : 2ページ目動画
- `assets/03.png`〜`assets/14.png` : 3ページ目以降の静止画
- `assets/01-poster.png`, `assets/02-poster.png` : 動画読み込み前の表示画像

## 設定済みリンク

- LINE: https://lin.ee/tzZWkAf
- Instagram: https://www.instagram.com/kurumi.totonoe?igsh=aThncjYwMG94OGk2&utm_source=qr
- note: https://note.com/kurumi06506

## Vercelに投げる流れ

1. ZIPを解凍
2. 中身をGitHubのリポジトリにアップロード
3. VercelでGitHubリポジトリをImport
4. Framework PresetはOtherのままでOK
5. Deploy

## 注意

最終ページのボタンは、画像の上に透明リンクを重ねています。
ボタン位置をCanva側で大きく変更した場合は、`index.html` の `.hotspot` の `left/top/width/height` を調整してください。
