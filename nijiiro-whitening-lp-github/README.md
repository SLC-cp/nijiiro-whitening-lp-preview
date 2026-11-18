# にじいろ歯科 ボーテ式ホワイトニング LP（プレビュー）

静的な1ページのLPです。ビルド不要で、そのままGitHub Pagesで公開できます。

## 構成

```
index.html        … ページ本体（CSS・JSを内包）
.nojekyll         … GitHub PagesでJekyll処理を無効にする空ファイル
images/           … 差し替えた画像（FV、特徴、コース、MENU、CONTACT など）
images/assets/    … 元ページから取り出した画像・アイコン（ファイル名はハッシュ）
```

## GitHub Pagesで公開する手順

1. GitHubで新しいリポジトリを作成します。
2. このフォルダの中身（`index.html`、`.nojekyll`、`images/`）を、リポジトリ直下にアップロードします。
3. リポジトリの Settings → Pages で、Branch を `main`（root）に設定します。
4. 数分後、`https://<ユーザー名>.github.io/<リポジトリ名>/` で表示されます。

## 注意

- `index.html` には `noindex,nofollow` が入っています（プレビュー用）。公開時は検索に載せたい場合に削除してください。
- Instagramのセクションは、公式の埋め込み（`//www.instagram.com/embed.js`）を使っています。表示する3投稿は、`index.html` 内の投稿URLを書き換えて入れ替えます。
- 画像のパスはすべて相対パスです。フォルダ構成を変えないでください。
