# apps-site

Ichirin のアプリ共通サイト（GitHub Pages）。

- `/` トップ：Ichirin の紹介とアプリ一覧
- `/<アプリ名>/` アプリの紹介・`privacy/`・`support/`

## アプリを追加するとき
1. `hidane/` をまねて `/<アプリ名>/` フォルダを作る（`index.html`・`privacy/index.html`・`support/index.html`・`images/`）
2. トップの `index.html` の `.app-list` に `<li>` を1つ足す
