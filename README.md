[![GitHub Actions Status Badge](https://github.com/coderdojo-japan/dojocon2019.coderdojo.jp/workflows/Ruby/badge.svg)](https://github.com/coderdojo-japan/dojocon2019.coderdojo.jp/actions)

# DojoCon Japan 2019 公式サイト
![Cover Photo](https://github.com/coderdojo-japan/dojocon2019.coderdojo.jp/blob/master/img/main.png?raw=true)

## 投稿・追加のやりかた

### ワークショップ・スピーカー・スタッフの追加
1. ブラウザ上で [_data](https://github.com/coderdojo-japan/dojocon2019.coderdojo.jp/tree/master/_data) ディレクトリを開く
2. 対応するファイルを開く
   - :mortar_board: ワークショップ: [_data/workshops.yml](https://github.com/coderdojo-japan/dojocon2019.coderdojo.jp/blob/master/_data/workshops.yml)
   - :speaking_head: スピーカー: [_data/speaker.yml](https://github.com/coderdojo-japan/dojocon2019.coderdojo.jp/blob/master/_data/speaker.yml)
   - :busts_in_silhouette: スタッフ: [_data/staff.yml](https://github.com/coderdojo-japan/dojocon2019.coderdojo.jp/blob/master/_data/staff.yml)
   - :spiral_calendar: タイムテーブル: [_data/sessions.yml](https://github.com/coderdojo-japan/dojocon2019.coderdojo.jp/blob/master/_data/sessions.yml) (実装中) 🚧
3. 画面右にある ✎ アイコン (Fork this project and edit this file) をクリックする
4. 気になる箇所を修正し、修正内容にタイトルと説明文を付け、Propose file change をクリックする
5. 修正内容を確認し、問題なければ Create pull request をクリックする

以上で完了です。提案された内容は実行委員によって再確認され、問題なければ提案された内容が反映されます。もし問題があっても実行員会側で気付いて修正することができるので、まずはお気軽に提案してみてください ;)

### お知らせ・セッションの投稿
1. [_posts/template.md](https://github.com/coderdojo-japan/dojocon2019.coderdojo.jp/blob/master/_posts/template.md) ファイルをコピーする
1. コメントアウトを解除し、適宜情報を埋める
1. 各種ディレクトリに当該ファイルを追加する
   - :newspaper: :new: お知らせ用ディレクトリ: [_post/news/](https://github.com/coderdojo-japan/dojocon2019.coderdojo.jp/tree/master/_posts/news)
   - :woman_teacher: :man_teacher: セッション用ディレクトリ: [_post/session/](https://github.com/coderdojo-japan/dojocon2019.coderdojo.jp/tree/master/_posts/session)

### スポンサーの追加
1. スポンサー企業のロゴ画像を [img/sponsor/](https://github.com/coderdojo-japan/dojocon2019.coderdojo.jp/tree/master/img/sponsor) 内に配置。ファイル名は`sponsor-ランク名-企業名英語表記`
1. [_data/sponsors.yml](https://github.com/coderdojo-japan/dojocon2019.coderdojo.jp/blob/master/_data/sponsors.yml) の当該ランクカテゴリの下に、次のフォーマットで追記する
   ```
    - name: 企業名  
      img: 表示するロゴ画像のパス
      site: 企業のサイトURL
   ```

## 動かしかた (開発者向け)
Jekyllで動いているので、ローカル環境で開発する場合はJekyllとNode.jsをセットアップしてください。

表示のさせ方です。

1. `$ bundle install`
1. `$ bundle exec jekyll server`
1. [localhost:4000](http://localhost:4000/) にアクセス
