# 洗車カンペ PWA

Cloudflare Pages向けの静的PWAです。DB不要です。

## 配置ファイル
- index.html
- manifest.webmanifest
- sw.js
- icon.svg
- icon-192.png
- icon-512.png

## Cloudflare Pages
1. このフォルダをGitHubリポジトリへpush
2. Cloudflare Pagesでリポジトリ接続
3. Framework preset: None
4. Build command: 空欄
5. Build output directory: /
6. カスタムドメインで `wash.example.com` 等を設定

## 補足
- iK FOAM Pro 2は実用容量1.25L基準
- 設定はlocalStorageのみ
- 洗車履歴DBは使用しません
- Service Workerにより一度読み込めばオフライン使用可能
