# CashFlow Manager

クレカ返済・出金による複数口座の残高推移をシミュレーションするPWAアプリです。

## GitHub Pages での公開手順

1. このリポジトリを GitHub に push する
2. GitHub リポジトリの **Settings** → **Pages** を開く
3. **Source** を `Deploy from a branch` に設定
4. **Branch** を `main`、フォルダを `/ (root)` に設定して **Save**
5. 数分後に `https://<ユーザー名>.github.io/<リポジトリ名>/` でアクセス可能になる

## ファイル構成

```
/
├── index.html      # メインアプリ
├── manifest.json   # PWA設定
├── sw.js           # Service Worker
├── icon-192.png    # アイコン
├── icon-512.png    # アイコン
└── README.md       # このファイル
```

## スマホのホーム画面への追加

- **iPhone**: Safari で開き「共有」→「ホーム画面に追加」
- **Android**: Chrome で開き「メニュー」→「ホーム画面に追加」
