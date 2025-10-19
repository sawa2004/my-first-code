# my-first-code

GitHub Issues を掲示板ログとして閲覧できるシンプルな Web アプリです。  
公開ページ: https://sawa2004.github.io/my-first-code/

## アプリの概要
- `sawa2004/my-first-code` リポジトリの Issue を一覧表示します。
- モバイル端末でも読みやすいカードレイアウトとライト/ダークテーマに対応しています。
- 「投稿する」ボタンから GitHub の Issue 作成画面に遷移し、新規投稿ができます。
- 追加読み込みボタンで過去の投稿を順番に取得できます。

## 使い方
1. ブラウザで https://sawa2004.github.io/my-first-code/ にアクセスします。
2. 最新の Issue が自動的に読み込まれて表示されます。
3. 投稿を開きたい場合はカード内の「詳細を見る →」リンクをクリックします。
4. 新しい投稿はページ上部の「投稿する（GitHub Issue）」ボタンから Issue 作成画面に移動して行います。

## Google Sites に埋め込む
Google Sites など iframe 埋め込みに対応したサービスでは、以下のように `index.html` を直接読み込んで利用できます。

```html
<iframe
  src="https://sawa2004.github.io/my-first-code/"
  width="100%"
  height="800"
  style="border:0;"
  allowfullscreen
></iframe>
```

## 注意事項
- GitHub の未認証 API を利用しているため、短時間に大量アクセスを行うとレートリミットに達することがあります。
- 埋め込み先の CSP（コンテンツセキュリティポリシー）設定によっては、外部ページの表示が制限される場合があります。
