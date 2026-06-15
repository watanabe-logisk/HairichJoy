# Hair Rich Joy（ヘアーリッチ・ジョイ）

山梨県・山中湖にあるヘアサロン「Hair Rich Joy」の公式ウェブサイト（1ページ構成の静的サイト）です。

## 構成

```
.
├── index.html        # サイト本体（HTML / CSS / JS すべて内包）
├── assets/           # 画像
│   ├── exterior.jpg
│   ├── hours-sign.jpg
│   ├── lounge-real.jpg
│   └── reception-real.jpg
├── .nojekyll         # GitHub Pages 用（処理をスキップ）
└── README.md
```

外部依存は Google Fonts のみで、ビルド作業は不要です。`index.html` をブラウザで開けばそのまま表示できます。

## GitHub Pages での公開手順

1. このフォルダの中身をリポジトリにアップロード（コミット）します。
2. リポジトリの **Settings → Pages** を開きます。
3. **Build and deployment** の **Source** を「Deploy from a branch」にします。
4. Branch を `main`（フォルダは `/root`）に設定して保存します。
5. 数分後に表示される URL でサイトが公開されます。

> サブフォルダ（例: `site/`）のままアップロードした場合は、その中身をリポジトリ直下に置くか、Pages の公開フォルダ設定を合わせてください。

## ローカルでの確認

```bash
# 例: Python の簡易サーバー
python3 -m http.server 8000
# → http://localhost:8000 にアクセス
```
