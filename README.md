# 余白スタンド

野球から、ゲームと道具の話まで扱う個人ブログです。ビルド不要の静的サイトなので、Cloudflare Pagesへそのまま公開できます。

## Cloudflare Pagesで公開

1. GitHubで `yohaku-stand` というPublicリポジトリを作成します。
2. このフォルダ内のファイルをリポジトリ直下へアップロードします。
3. Cloudflareの「Workers & Pages」からPagesを作り、GitHubのリポジトリを接続します。
4. Framework presetは `None`、Build commandは空欄、Build output directoryは `/` にします。
5. 公開後に発行されたURLを確認します。

## 公開前に必要な更新

- `about.html` にハンドルネームと自己紹介を記載
- `contact.html` に問い合わせ先を設定
- Amazonアソシエイト参加後、フッター表記を正式な内容に更新
- 公開URL確定後、canonical・OG URL・sitemap.xmlを追加

## 記事の追加

記事は `articles/` に保存します。記事追加時は、トップページと `articles/index.html` の記事一覧も更新します。
