---
layout: default
copy: "- つぎのSTEP -"
---
<section class="top">
  <!--<img src="{{site.url}}/img/dojocon_brown_oneline.png" alt="DojoConJapan2019" class="top-title-big top-title">
  <img src="{{site.url}}/img/dojocon_brown.png" alt="DojoConJapan2019" class="top-title-small top-title">-->
  <img src="{{site.url}}/img/cloud.png" class="top-cloud" alt="Cloud">

  <h1>DojoCon Japan <br>2019</h1>
  <div class="top-theme"><img src="{{site.url}}/img/svg/right.svg" alt="Right" class="top-right"> つぎのSTEP</div>
  <p class="top-date">12.21<span>SAT</span></p>
  <p class="top-venue">in<br class="ph"> 名城大学 ナゴヤドーム前キャンパス<br class="ph"> 社会連携ゾーンshake</p>

  <img src="{{site.url}}/img/ninja.png" alt="(´∀｀*)" class="top-ninja">
</section>
<img src="{{site.url}}/img/background.png" class="top-background" alt="Background">
<section id="about">
  <h2>DojoCon Japan 2019</h2>
  <div class="text">
    <h3>日本最大のCoderDojoの祭典</h3>
    <p>DojoCon Japan は日本のCoderDojoの主催者やメンター、プログラミングを学ぶ子ども達とその活動に賛同・協賛する人が全国各地から集まる大きなイベントです。2016年～2017年は大阪、2018年は東京で開催されました。本年は名古屋で4回目の開催を行います。今年のDojoConのテーマは「つぎのSTEP」です。全国のDojoの新たな取り組みが共有されることで、各地のDojoが新たな活動の手掛かりを見つけ、今後のDojoがさらに発展することを目的としています。</p>
  </div>
  <div class="text">
    <h3>CoderDojoとは</h3>
    <p>2011年にアイルランドから始まった、子ども達にプログラミングを学ぶ場を提供するボランティア主導の非営利活動です。この活動では、ボランティアの大人たちと学びたい子どもたちとで作る場をDojoと呼んでいます。CoderDojoの輪は世界100カ国、1800カ所以上に広がり、ここ日本では185カ所以上のDojoで毎年1,000回以上 (*1) 開催されています。<br>*1 統計情報: https://coderdojo.jp/stats</p>
  </div>
</section>
<div class="background-ninja">
<section id="outline">
  <h2>ABOUT</h2>
  <p class="caption">開催概要</p>
  <div class="text">
    <div class="outline-one">
      <h3>開催日</h3>
      <p>2019年12月21日（土）</p>
    </div>
    <div class="outline-one">
      <h3>時間</h3>
      <p>10:30-17:30（開場10:00）※予定</p>
    </div>
    <div class="outline-one">
      <h3>場所</h3>
      <p>名城大学 ナゴヤドーム前キャンパス社会連携ゾーンshake</p>
    </div>
    <div class="outline-one">
      <h3>参加費</h3>
      <p>無料</p>
    </div>
    <p>※参加には事前の申し込みが必要となります。<br>イベント終了後、懇親会の開催を予定しております。</p>
  </div>
  <a href="https://dojocon-japan.doorkeeper.jp/" class="button" target="_blank">申し込みをする</a>
</section>
</div>
<section id="access">
  <h2>ACCESS</h2>
  <p class="caption">会場の場所</p>
  <iframe class="map" src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d3260.69697362165!2d136.9440337!3d35.1891045!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x6003119bbc4c9fc5%3A0xd5c643a8df7fc59!2z5ZCN5Z-O5aSn5a2mIOODiuOCtOODpOODieODvOODoOWJjeOCreODo-ODs-ODkeOCuQ!5e0!3m2!1sja!2sus!4v1568871387623!5m2!1sja!2sus" loading="lazy" width="600" height="450" frameborder="0" style="border:0;" allowfullscreen=""></iframe>
  <div class="text">
    <h3>名城大学 ナゴヤドーム前キャンパス 社会連携ゾーンshake</h3>
    <p>愛知県名古屋市東区矢田南 4-102-9</p>
    <p>JR中央本線・名鉄瀬戸線「大曽根」駅下車 徒歩約10分。地下鉄名城線 「ナゴヤドーム前矢田」駅下車2番出口 徒歩約3分。ゆとりーとライン「ナゴヤドーム前矢田」駅から徒歩約5分</p>
  </div>
</section>
<div class="background-ninja">
<section id="news">
  <h2>NEWS</h2>
  <p class="caption">お知らせ</p>
  {% for post in site.categories.news %}
    {% include articles.html %}
  {% endfor %}
</section>
</div>
<section id="workshops">
  <h2>WORKSHOP</h2>
  <p class="caption">ワークショップ</p>
  <div class="img-section">
    <img src="{{site.url}}/img/workshop.jpg" alt="Workshop"> <!--ここに画像のパスを設定するとセクションのイメージ画像として表示されます。-->
  </div>
  {% for post in site.categories.workshop %}
    {% include workshops.html %}
  {% endfor %}
</section>
<div class="background-ninja">
<section id="sessions">
  <h2>SESSION</h2>
  <p class="caption">セッション</p>
  <div class="img-section">
    <img src="{{site.url}}/img/session.jpg" alt="Session"> <!--ここに画像のパスを設定するとセクションのイメージ画像として表示されます。-->
  </div>
  {% for post in site.categories.session %}
    {% include sessions.html %}
  {% endfor %}
</section>
</div>
<section id="contest">
  <h2>CONTEST</h2>
  <p class="caption">コンテスト</p>
  <article class="article article-contest">
    <img src="{{site.url}}/img/goglobal_thumbnail.png" alt="Contest" class="article-thumbnail">
    <h3>GO GLOBAL! プログラミングコンテスト 作品募集！</h3>
    <p>子ども達に海外の文化やコミュニティーにふれてもらいたい。その思いから、昨年に続き今年も『ソニックガーデン presents Go Global! DojoCon Japan 2019 プログラミングコンテスト』を開催いたします。最優秀賞受賞者は、アイルランドで2020年6月頃に開催されるCoolest Projectsへご招待します。</p>
    <a href="{{site.url}}/contests/1" class="button">
      もっと見る
    </a>
  </article>
</section>

<section id="sponsors">
  <h2>SPONSORS</h2>
  <p class="caption">スポンサーさま</p>
  <!-- /_data/sponsors.ymlからランクごとに読み込んで表示している。もっとスマートになるはず… -->
  <h3>Gold Sponsors</h3>
  <div class="sponsors-rank">
    {% for sponsor in site.data.sponsors.gold %}
    <a href="{{sponsor.site}}" target="_blank">
    <img src="{{site.url}}/img/sponsor/{{sponsor.img}}" alt="{{sponsor.name}}" class="sponsor-gold sponsors-rank-img">
    </a>
    {% endfor %}
  </div>

  <h3>Silver Sponsors</h3>
  <div class="sponsors-rank">
    {% for sponsor in site.data.sponsors.silver %}
    <a href="{{sponsor.site}}" target="_blank">
    <img src="{{site.url}}/img/sponsor/{{sponsor.img}}" alt="{{sponsor.name}}" class="sponsor-silver sponsors-rank-img">
    </a>
    {% endfor %}
  </div>

  <h3>Bronze Sponsors</h3>
  <div class="sponsors-rank">
    {% for sponsor in site.data.sponsors.bronze %}
    <a href="{{sponsor.site}}" target="_blank">
    <img src="{{site.url}}/img/sponsor/{{sponsor.img}}" alt="{{sponsor.name}}" class="sponsor-bronze sponsors-rank-img">
    </a>
    {% endfor %}
  </div>
  <h3>In-kind Sponsors</h3>
  <div class="sponsors-rank">
    {% for sponsor in site.data.sponsors.in-kind %}
    <a href="{{sponsor.site}}" target="_blank">
    <img src="{{site.url}}/img/sponsor/{{sponsor.img}}" alt="{{sponsor.name}}" class="sponsor-in-kind .sponsors-rank-img">
    </a>
    {% endfor %}
  </div>
  <h3>Individual Sponsors</h3>
  <div class="sponsors-rank">
    <ul class="individual">
    {% for sponsor in site.data.sponsors.individual %}
    <li>{{sponsor.name}}</li>
    {% endfor %}
    </ul>
  </div>
</section>

<section id="coderdojo-foundation">
  <h2>UNDER THE AUSPICE OF</h2>
  <p class="caption">後援</p>
  <ul class="list-simple">
    <li><a href="https://coderdojo.com/" target="_blank">CoderDojo Foundation</a></li>
    <li><a href="https://coderdojo.jp/" target="_blank">CoderDojo Japan</a></li>
  </ul>
</section>

<div class="background-ninja">
<section id="contactme">
  <h2>CONTACT</h2>
  <p class="caption">お問い合わせ</p>
  <a href="https://forms.gle/pc82bDDD8a1iGHpX7" class="button" target="_blank">フォームを開く</a>
</section>
</div>
<!--<section id="sns">
  <h2>SNS</h2>
</section>-->

<section id="staff">
  <h2>STAFF</h2>
  <p class="caption">実行委員のみなさん</p>
  {% for staff in site.data.staff %}
  <div class="staff">
    {% if staff.site %}
    <a href="{{staff.site}}" target="_blank" rel="nofollow">
    {% endif %}
    <div class="staff-image">
      {% if staff.img %}<img src="{{site.url}}/img/staff/{{staff.img}}" alt="{{staff.name}}" loading="lazy">
      {% else %}<img src="{{site.url}}/img/staff/dummy.png" alt="{{staff.name}}" loading="lazy">
      {% endif %}
    </div>
    <p>{{staff.name}}</p>{% if staff.site %}</a>{% endif %}
  </div>
  {% endfor %}
</section>
