# Kurumi Worldview LP

Vercelにそのままアップできる静的HTML一式です。

## ファイル構成

- `index.html`：LP本体
- `images/01.jpg`〜`images/14.jpg`：LP各ページ画像
- `package.json`：Vercel用（任意）

## 設定済みリンク

- LINE：https://lin.ee/VchYwLy
- Instagram：https://www.instagram.com/kurumi.totonoe?igsh=aThncjYwMG94OGk2&utm_source=qr
- note：https://note.com/kurumi06506
- Threads：https://www.threads.com/@kurumi.totonoe?igshid=NTc4MTIwNjQ2YQ==

## Vercelに投げる流れ

1. このフォルダ一式をGitHubにアップロード
2. Vercelで「New Project」
3. GitHubのリポジトリを選択
4. Framework Preset は `Other` または自動判定のままでOK
5. Deploy

## 注意

最後のページは、LINE / Instagram / note / Threads のリンクを透明ボタンで重ねています。
Canva側で最後のページのボタン位置を変えた場合は、`index.html` の `style="left:... top:..."` を調整してください。
