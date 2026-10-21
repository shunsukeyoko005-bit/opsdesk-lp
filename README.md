# static-lp（ビルド不要プレビュー）

Next.js（`apps/web`）がこの環境で `npm install` できない場合の**代替静的LP**です。

- 開き方: `index.html` をブラウザで開く、または任意の静的ホスティングへフォルダごと配置
- 購入CTAは BOOTH URL 未設定のため無効（意図的）
- `noindex` 固定。本番は Next 側の環境変数と公開承認後に切り替えること

本番の正本は引き続き `apps/web`（Next.js）です。
