# 日本の飲食店オープンデータ

これは[テイクアウト&デリバリーMAP powered by Toreta](https://takeout-delivery-map.toreta.in/) を通じて収集された飲食店情報をどなたでも二次利用できるように公開したものです。

## 目的

元々[テイクアウト&デリバリーMAP powered by Toreta](https://takeout-delivery-map.toreta.in/)はCOVID-19感染予防の為の自粛要請により厳しい状況下にある飲食店を支援するために開発したものです。<br>
このマップを通じて収集された飲食店データが活用されることで最終的には飲食産業の活性化に寄与することが目的です。

## データの収集元について

本データは下記情報元から収集しています。
- ユーザーからの登録
- 店舗からの登録
- 自社による登録
- その他の情報提供元
 - [神奈川県](https://www.pref.kanagawa.jp/docs/k8d/prs/r1058152.html)
 - [横浜市](https://www.city.yokohama.lg.jp/business/kigyoshien/syogyo/covid-19/takeout-delivery/takeout.html)
 - [Save the tables](https://savethetables.org/)
 - [うちたべ](https://uchitabe.com/)

公開している各種データについては、[クリエイティブ・コモンズ・ライセンス表示4.0国際](https://creativecommons.org/licenses/by/4.0/deed.ja) のもとでライセンスされています。

## 免責

「restaurants-opendata-in-japan」に公開するデータ使用、名称や内容等の改変や削除、サービスの停止等により、利用者及び第三者に生じた損害等については、株式会社トレタは一切責任を負いません。

## カラム（内容/データ型）
※：飲食店によってはブランクの可能性あり
- name（店舗名漢字/string)
- kana（店舗名カタカナ/string) ※
- zip（郵便番号/string)
- prefecture(都道府県/string)
- city(市区町村/string)
- street(番地/string)
- building(建物名/string) ※
- station(最寄り駅/string) ※
- phone(店舗電話番号/string) ※
- genre(ジャンル/string)
- takeout(テイクアウト対応有無/boolean)
- delivery(デリバリー対応有無/boolean)
- takeoutUrl(テイクアウト注文詳細のURL/string) ※
- deliveryUrl(デリバリー注文詳細のURL/string) ※
- siteUrl(店舗のホームページURL/string) ※
- eatinUrl(店内利用予約用のURL/string) ※
- emoney(電子マネー対応有無/boolean) ※
- credit(クレジットカード対応有無/boolean) ※
- private(個室有無/boolean) ※
- nosomoking(完全禁煙対応有無/boolean) ※
- easyaccess(バリアフリー対応有無/boolean) ※
- close(定休日/string) ※
- time(営業時間/string) ※
- seats(席数/number) ※
- lat(緯度/number)
- Ing(経度/number)

## 問い合わせ

下記までご連絡ください。<br>
https://forms.gle/GpvjgBdsNySgugLC6

## 運営元

株式会社トレタ<br>
https://corp.toreta.in/
