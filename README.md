# Russian Guide Website

ロシア語ガイド レーナの GitHub Pages 用静的サイトです。

## 構成

- `index.html`: 言語選択ページ
- `ja/index.html`: 日本語ページ
- `ru/index.html`: ロシア語ページ
- `ru/destinations/`: ロシア語の各地ギャラリーページ
- `assets/images/DSCN0180.jpeg`: 共通画像
- `assets/css/style.css`: 共通スタイル
- `assets/js/main.js`: 共通スクリプト
- `.github/workflows/deploy-pages.yml`: GitHub Pages デプロイ

## GitHub Pages 設定

このリポジトリは GitHub Actions で Pages にデプロイされます。

1. GitHub の `Settings` → `Pages` を開く
2. `Build and deployment` の `Source` を `GitHub Actions` に設定
3. `main` ブランチへ push すると自動デプロイ

## ローカル確認

静的ファイルのため、VS Code の Live Server などで表示確認できます。
