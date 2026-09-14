# fitcare-legal

「フィットケア」（`com.hiromu.fitcare`）の利用規約・プライバシーポリシーを
GitHub Pagesで公開するための、**このページ専用の独立リポジトリ**です。

アプリ本体のソースコード（別リポジトリ、非公開）は一切含みません。
App Store Connectの「プライバシーポリシーURL」欄・アプリ内のリンクからは、
このリポジトリをGitHub Pagesで公開したURLを参照します。

## 公開手順

1. GitHubのリポジトリ画面 → Settings → Pages →
   「Build and deployment」の Source を `Deploy from a branch` に設定、
   Branch を `main` / `/ (root)` にして Save
2. 数分後、`https://sugimoto-hiromu.github.io/fitcare-legal/` で公開される
3. 公開されたURLを、Xcodeプロジェクト側のプライバシーポリシーリンク・
   App Store Connectの該当欄へ反映する

## 更新方法

`privacy.html`・`terms.html`を編集し、最終更新日を書き換えてから再度pushするだけで、
GitHub Pagesは自動的に再デプロイされる。
