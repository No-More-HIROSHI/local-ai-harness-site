# local-ai-harness-site

`local-ai-harness`（ローカルAIの作業支援ツール）の公開ページ。Google Cloud のログイン設定（Google Auth Platform の「ブランディング」）で、アプリのホームページ・プライバシーポリシー・利用規約の URL に使う。これがないと、ログインの許可が7日で切れる「テスト中」から「本番環境」に切り替えられない。

- `index.html`：紹介ページ（何をするツールか）
- `privacy.html`：プライバシーポリシー
- `terms.html`：利用規約

GitHub Pages（main ブランチのルート）で公開。URL は https://no-more-hiroshi.github.io/local-ai-harness-site/

local-ai-harness で扱う情報や外部サービスが変わったら（例：Notion・Claude API・検索サービスの追加や変更）、`privacy.html` も直す。
