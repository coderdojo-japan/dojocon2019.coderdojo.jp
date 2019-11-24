[![GitHub Actions Status Badge](https://github.com/coderdojo-japan/dojocon2019.coderdojo.jp/workflows/Ruby/badge.svg)](https://github.com/coderdojo-japan/dojocon2019.coderdojo.jp/actions)

# DojoCon Japan 2019 公式サイト
![Cover Photo](https://github.com/coderdojo-japan/dojocon2019.coderdojo.jp/blob/master/img/main.png?raw=true)

## 動かしかた
Jekyllで動いているので、ローカル環境で開発する場合はJekyllとNode.jsをセットアップしてください。

表示のさせ方です。

1. `$ bundle install`
1. `$ bundle exec jekyll server`
1. [localhost:4000](http://localhost:4000/) にアクセス

## 投稿・追加のやりかた

### お知らせ記事の投稿
[_posts/template.md](https://github.com/coderdojo-japan/dojocon2019.coderdojo.jp/blob/master/_posts/template.md) ファイルをコピーして、適宜情報を埋めて、[_post/news/](https://github.com/coderdojo-japan/dojocon2019.coderdojo.jp/tree/master/_posts/news) に追加する

### ワークショップ追加
[_data/workshops.yml](https://github.com/coderdojo-japan/dojocon2019.coderdojo.jp/blob/master/_data/workshops.yml) 参照

### セッション追加
[_posts/template.md](https://github.com/coderdojo-japan/dojocon2019.coderdojo.jp/blob/master/_posts/template.md) ファイルをコピーして、適宜情報を埋めて、[_post/session/](https://github.com/coderdojo-japan/dojocon2019.coderdojo.jp/tree/master/_posts/session) に追加する

### タイムテーブル追加 (未公開)
[_data/sessions.yml](https://github.com/coderdojo-japan/dojocon2019.coderdojo.jp/blob/master/_data/sessions.yml) 参照

### スピーカー追加
[_data/speaker.yml](https://github.com/coderdojo-japan/dojocon2019.coderdojo.jp/blob/master/_data/speaker.yml) 参照

### スポンサー追加
1. 画像を [img/sponsor/](https://github.com/coderdojo-japan/dojocon2019.coderdojo.jp/tree/master/img/sponsor) 内に配置。ファイル名は`sponsor-ランク名-企業名英語表記`
1. [_data/sponsors.yml](https://github.com/coderdojo-japan/dojocon2019.coderdojo.jp/blob/master/_data/sponsors.yml) の任意のランクカテゴリ下に次の内容を記入する
   ```
    - name: 企業名  
      img: 表示するロゴ画像のパス
      site: 企業のサイト
   ```

### スタッフ追加
[_data/staff.yml](https://github.com/coderdojo-japan/dojocon2019.coderdojo.jp/blob/master/_data/staff.yml) 参照

