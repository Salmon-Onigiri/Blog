---
layout: post
title: "ここにタイトルを入れる" #タイトルを入力
date: 2020-mm-dd 11:00:00 +0900 #年月日を入力
excerpt: "●●●●□●●●●□●●●●□●●●●□●●●●□●●●●□・・・" #home画面でタイトルの下に表示される短文を入力
categories: [Cyber, Gadget] #EverNoteの「GitHubPages」の「Category & Tag」を参照
# [Cyber] ホームページ，ブログ，その他，PC，ネット関係
# [Gadget] 自転車，時計，スマホ，タブレットなど気の利いた小道具類をタグで分ける
# [Gourmet] レストラン，食材，料理，酒，チーズなどをタグで分ける
# [Travel] 場所，目的，アトラクションなどをタグで分ける？
# [Favorite] 趣味的なもの．テレビ，映画，本，音楽，美術などをタグで分ける
# [Car] 自動車関連．ドライブ，メンテ，トラブル・・・などをタグで分ける
# [Life] 日常生活関連．上に入らない暮らし絡みはすべて・・・タグは下の中で相当がなければmiscsに
# [Business] 仕事関連．タグは下の中で相当がなければmiscsに
tag: [GitHubPages, bycycle] #EverNoteの「GitHubPages」の「Category & Tag」を参照
# [GitHubPages]
# [bycycle]
# [watch]
# [smart phone]
# [computer]
# [app]
# [work]
# [food]
# [drink]
# [cheese]
# [brand]
# [shop]
# [restaurant]
# [art]
# [book]
# [music]
# [movie]
# [television]
# [fitness]
# [sport]
# [drive]
# [maintenance]
# [trouble]
# [miscs]
comments: true
---

画像の入れ方
![三井商船フェリー・さんふらわあ](https://salmon-onigiri.github.io/blog/img/201009_001.png){: .linksmall}
![太平洋フェリー](https://salmon-onigiri.github.io/blog/img/201009_002.png){: .linksmall}

リンクの入れ方
[三浦綾子](https://amzn.to/36wwlZb){: target="_blank"}さんといえば，  


### GitHub PagesのためのフォルダをDropboxに置いたら楽だった

**プログラミング**の「プ」の字も知らない素人が[**GitHub Pages**][gp]{:target="_blank"}を使って公開しているこのブログ，  
公開に至るまでには，実にいろいろな人のブログやサイトを参考に**試行錯誤**を繰り返してきた．

[**GitHub Pages**][gp]{:target="_blank"}本家のインストラクションや先人たちの知恵を借りて，  
ほとんど触ったことなどない**ターミナル**を恐る恐る開いて，
何も考えずに[**GitHub Pages**][gp]{:target="_blank"}をつくってみると，  
当然のことながらユーザーのディレクトリの直下にフォルダができた．

#### へぇ・・・こんなふうにできるわけか．

最初はそれで**感動していた**のだが，  
<span style="color: #8d7edc;"><strong>別のマシン</strong></span>からアクセスしようとしてハタと困ったことに気がついた．

<span style="color: #8d7edc;"><strong>最初のマシン</strong></span>でつくった[**GitHub Pages**][gp]{:target="_blank"}のフォルダにアクセスするには・・・どうすりゃいいんだ？

そもそも[**GitHub**][gh]{:target="_blank"}はクラウド上にデータがあって，  
さまざまな人が**共有**しながら作業をするためのプラットフォームなのだから，  
**どこで**つくっていようが問題なく**共有**できるわけなのだけれど，  
そのためにターミナルを開いたり慣れないコマンドを打ち込んだりなんかしたくないし・・・

待てよ，そもそも最初にGitHub Pagesのフォルダをつくるときに，  
[**Dropbox**][db]{:target="_blank"}につくってしまえば，どこからどのマシンでアクセスしようが，  
一発で解決できちゃうんじゃないの？

でもって[**Dropbox**][db]{:target="_blank"}の中に[**GitHub Pages**][gp]{:target="_blank"}用のフォルダをつくってみると・・・

#### （たまたま）ご名答！

あっさりほかのマシンでも，  
問題なくブログをいじれるようになってくれたと，  
そんなこと．

<a href="https://www.amazon.co.jp/GitHub%E5%AE%9F%E8%B7%B5%E5%85%A5%E9%96%80%E2%94%80%E2%94%80Pull-Request%E3%81%AB%E3%82%88%E3%82%8B%E9%96%8B%E7%99%BA%E3%81%AE%E5%A4%89%E9%9D%A9-WEB-PRESS-plus-ebook/dp/B07JLJSDMJ/ref=as_li_ss_il?__mk_ja_JP=%E3%82%AB%E3%82%BF%E3%82%AB%E3%83%8A&keywords=GitHub&qid=1577256598&sr=8-5&linkCode=li2&tag=palibera-22&linkId=4aec90359112a8a8ccb139c8ec9f87f5&language=ja_JP" target="_blank"><img border="0" src="//ws-fe.amazon-adsystem.com/widgets/q?_encoding=UTF8&ASIN=B07JLJSDMJ&Format=_SL160_&ID=AsinImage&MarketPlace=JP&ServiceVersion=20070822&WS=1&tag=palibera-22&language=ja_JP" ></a><img src="https://ir-jp.amazon-adsystem.com/e/ir?t=palibera-22&language=ja_JP&l=li2&o=9&a=B07JLJSDMJ" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" />  

[db]: https://www.dropbox.com/
[gh]: https://github.com
[gp]: https://pages.github.com
