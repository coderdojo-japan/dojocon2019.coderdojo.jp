[![GitHub Actions Status Badge](https://github.com/coderdojo-japan/dojocon2019.coderdojo.jp/workflows/Ruby/badge.svg)](https://github.com/coderdojo-japan/dojocon2019.coderdojo.jp/actions)

# DojoCon Japan 2019 Webサイト案
yuki384によるWebサイト案です。

## 動かしかた
Jekyllで動いているので、ローカル環境で開発する場合はJekyllとNode.jsをセットアップしてください。

表示のさせ方です。

1. `$ bundle install`
1. `$ bundle exec jekyll server`
1. [localhost:4000](http://localhost:4000/) にアクセス

## できていること
- トップページの表示
- 基本的な情報の掲載
- ニュース・ワークショップ・セッション の記事をmdファイルから変換してトップに表示
- `_data`内のymlファイルからのスタッフ一覧取得・表示
- スポンサーの掲載とランクに応じた表示(`_data`内のymlファイルで管理)
  - Goldは幅いっぱい、Silverは半分、BronzeとIn-kindは5等分
- Facebook・Twitterシェアボタン設置
- ヘッダー・フッターの実装
- お知らせ・セッション・ワークショップの詳細ページ
- セッションのスピーカーを`_data`内のymlファイルで管理・表示
- URLのカスタム(詳しくは `/_posts/template.md`)

## toDo
まだ実装できていないものです。
- 記事の掲載
- スピーカー詳細ページ
- タイムテーブル
- トップ画像・タイトルロゴの表示(デザインがコーディングに追いついていないです)
- スタッフ、ニュース、アクセス、開催概要 などのレスポンシブ対応
- ファビコン
- OGP画像
- 行動規範
- その他細かいデザイン
  - 本当は「見出しを巻物風デザインにしたい」「ここ余白足りないな」などデザイン面で改善点がたくさんあるのですが、CSSは基本的なHTMLができていれば後で好きなだけ書けますので、まずは記事やスピーカーの情報管理の部分を実装しました。
