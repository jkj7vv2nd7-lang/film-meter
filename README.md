# FILM METER No.8 — 露出計 × 距離計

古いフィルムカメラ用のスマホ対応Webアプリ。単体ファイルで動作します。

- 🎞 露出計: カメラ測光 / 照度センサー / Sunny16、手動EV
- 📐 距離計: 被写界深度 + 高さ×俯角 + 大きさから推定
- 📱 スマホ最適化・アナログデザイン

## 使い方

`index.html` をブラウザで開くだけ（カメラ使用時は HTTPS 必須）。

## Vercelにデプロイ

1. https://vercel.com/new でこのリポジトリを Import
2. Framework Preset は `Other`、Build Command は空のまま Deploy

CLIでやる場合:

```bash
npx vercel login
npx vercel --prod
```
