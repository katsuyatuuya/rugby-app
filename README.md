# TAG RUGBY 2026

タグラグビーのチーム運営用シングルファイルアプリです。

## ファイル構成

- `index.html`: アプリ本体
- `タグラグビーアプリ仕様書.md`: 仕様メモ

## 保存仕様

- 通常操作の保存先はブラウザの `localStorage`
- ホーム画面の「データ管理」から JSON バックアップの書き出しと読み込みが可能
- 端末変更やブラウザデータ削除に備えて、定期的にバックアップ保存を実行する前提

## GitHub での更新手順

```powershell
git add .
git commit -m "更新内容"
git push
```

## 初回セットアップ

```powershell
git init
git branch -M main
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/<your-account>/<your-repo>.git
git push -u origin main
```
