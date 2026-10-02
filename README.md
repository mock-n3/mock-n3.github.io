# mock-n3.github.io

mock-n3 が公開している Chrome 拡張機能の関連ページ（プライバシーポリシーなど）を GitHub Pages で配信する。

- 公開URL: https://mock-n3.github.io/
- `main` ブランチの直下をそのまま配信する（ビルドなし。`.nojekyll` で Jekyll を止めている）

## ページの置き方

拡張機能ごとにフォルダを作り、ページごとに `index.html` を置く。URL は `/<拡張機能>/<ページ>/` になる。

| ページ | ファイル | URL |
|---|---|---|
| 一覧 | `index.html` | https://mock-n3.github.io/ |
| CO[:V] プライバシーポリシー | `cov/privacy/index.html` | https://mock-n3.github.io/cov/privacy/ |

新しい拡張機能やページを足したら、`index.html` の一覧にもリンクを足す。

## CO[:V] のプライバシーポリシーの更新

元の原稿は CO[:V] のリポジトリの `docs/privacy-policy.html`。版を上げるときはそちらを直してから、`cov/privacy/index.html` に同じ内容を写してプッシュする。公開URLは Chrome Web Store の「プライバシー」タブに登録しているので、場所を変えない。
