[![GitHub Actions Status Badge](https://github.com/coderdojo-japan/dojocon2019.coderdojo.jp/workflows/Ruby/badge.svg)](https://github.com/coderdojo-japan/dojocon2019.coderdojo.jp/actions)

# DojoCon Japan 2019 公式サイト

## 動かしかた
Jekyllで動いているので、ローカル環境で開発する場合はJekyllとNode.jsをセットアップしてください。

表示のさせ方です。

1. `$ bundle install`
1. `$ bundle exec jekyll server`
1. [localhost:4000](http://localhost:4000/) にアクセス

## 各項目追加のやりかた
### スポンサー追加
1. 画像を`/img/sponsor/`内に配置。ファイル名は`sponsor-ランク名-企業名英語表記`
1. `_data/sponsors.yml` の任意のランクカテゴリ下に次の内容を記入する
   ```
    - name: 企業名  
    img: 表示するロゴ画像のパス
    site: 企業のサイト
   ```

### スピーカー追加
`_data/speaker.yml`参照
### セッション・ワークショップ、お知らせ追加
`_posts/template.md`参照

### スタッフ追加
`_data/staff.yml`参照
