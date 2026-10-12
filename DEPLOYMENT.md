# スナップショット営業LPの公開

公開対象は `snapshot-lp-site.zip` に入っている静的サイトです。HTML、CSS、JavaScript、画像、紹介PDF、操作画面のサンプル、使用するライブラリとそのライセンスを含みます。

`.github/workflows/pages.yml` がZIPを展開してGitHub Pagesへ公開します。`main` のZIPまたは公開ワークフローを更新すると再公開されます。

## 更新方法

1. ZIPを空の作業ディレクトリに展開する。
2. `index.html`・`lp.css`・`lp.js`・`assets/` を必要に応じて編集する。
3. ZIP直下が `index.html` になるように、同じ名前でZIPを作り直す。
4. `snapshot-lp-site.zip` を更新して `main` に保存する。
5. Actions の `Publish Snapshot LP` が成功したことを確認する。

`.openai/hosting.json` や認証情報は公開パッケージに含めません。有料版の料金・機能は現在プラン案です。
