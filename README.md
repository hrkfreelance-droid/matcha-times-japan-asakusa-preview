# MATCHA TIMES Japan Asakusa Preview

🌐 **Preview Site**
[https://hrkfreelance-droid.github.io/matcha-times-japan-asakusa-preview/](https://hrkfreelance-droid.github.io/matcha-times-japan-asakusa-preview/)

MATCHA TIMES Japan Asakusaサイトの更新プレビュー（GitHub Pages）。
Tokyo（Asakusa店舗情報）→ Around the World（世界展開）→ Business（フランチャイズ案内）の順に構成。

このrepositoryはGitHub Pages確認専用です。**Netlify本番サイトとは接続されておらず、本番には一切反映されていません。**
本番: <https://matcha-times-japan-asakusa.netlify.app/> （今回は未変更）

## 構成

- `index.html` — メインページ（Asakusa店舗情報 / World / Franchise / Footer）
- `assets/` — 背景画像、ロゴ、アイコン、メニュー画像、フランチャイズPDFなど

## 国の追加方法

`index.html` 内の `countries` 配列（JavaScript）に1件追加するだけで、World Gridに反映されます。

```js
{ name: "国名", url: "https://...", status: "active" } // 稼働中
{ name: "国名", url: null, status: "coming-soon" }       // 準備中
```
