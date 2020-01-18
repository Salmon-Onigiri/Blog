---
layout: post
title:  "Atomでpushするためにはターミナルをいじれないとダメらしい"
date:   2020-01-18 13:00:00 +0900
excerpt: "このブログはAtomで書いてpushしているのだが，最初にpushするまえにしなければならなかったことは・・・"
categories: [General]
tag: [technical]
comments: true
---
### AtomでGitHubにpushできなかった時のメモ

この**ブログ**は[**GitHub**][gh]{:target="_blank_"}の公認エディタ的な位置づけの[**Atom**][am]{:target="_blank"_}で書いている．  
当然のことながら[**Atom**][am]{:target="_blank"_}と[**GitHub**][gh]{:target="_blank_"}の**親和性**は高く，  
[**Atom**][am]{:target="_blank"_}でテキストを書いてしまえば，そのままstageして**push**できる・・・はずだった．  

#### ところが・・・

某所で使っている**マシンA**（仮名）では，  
[**Atom**][am]{:target="_blank"_}を使ってテキストを書いてそのままstageして**push**すると，  
何の問題もなくpushできていた．  

ところが，別の場所の**マシンB**（仮名）にも[**Atom**][am]{:target="_blank"_}をインストールして，
同じプロジェクトを開いてテキストを書いて，  
同じように**push**しようとしたところ・・・  

「**Invarid username or password**」みたいな警告が出て，  
見事にリジェクトされてしまった．  

すべて**試行錯誤**でここまできた私にとっては，  
ひと度，「**動くハズ**」のことがうまくいかないと，  
その解決は**すべて難題**になるわけで・・・  

これまでと同じように**Googleさん**に問い合わせても，  
**キーワード**の選び方が悪いのか，  
**コレだ**という答えに出会えない．  

#### 何だ，ナンだ，何なんだ・・・  

しょうがないな・・・  
せっかくテキストを書いたんだし，  
ターミナルでコマンドを打ってpushするかと思い立ち，  
ゴニョゴニョやっていると，  
その途中で**username**と**password**の打ち込みを求められたではありませんか・・・

おや？  
これってもしや・・・  

ふたたび[**Atom**][am]{:target="_blank"_}で少しテキストをいじって，  
再度，[**Atom**][am]{:target="_blank"_}から**push**してみると，  

#### VOILA!

あっさり**push**できてしまいました．  
つまるところ，**マシンA**（仮称）では，  
ターミナルでGitHubに**commit**や**push**した後だったので，  
その段階でGit化したプロジェクトのフォルダに**ユーザー名**と**パスワード**が保存されていたらしく，  
[**Atom**][am]{:target="_blank"_}でもあっさり**push**できてしまったというわけ．  

<a href="https://www.amazon.co.jp/GitHub%E5%AE%9F%E8%B7%B5%E5%85%A5%E9%96%80%E2%94%80%E2%94%80Pull-Request%E3%81%AB%E3%82%88%E3%82%8B%E9%96%8B%E7%99%BA%E3%81%AE%E5%A4%89%E9%9D%A9-WEB-PRESS-plus-ebook/dp/B07JLJSDMJ/ref=as_li_ss_il?__mk_ja_JP=%E3%82%AB%E3%82%BF%E3%82%AB%E3%83%8A&keywords=GitHub&qid=1577256598&sr=8-5&linkCode=li2&tag=palibera-22&linkId=4aec90359112a8a8ccb139c8ec9f87f5&language=ja_JP" target="_blank"><img border="0" src="//ws-fe.amazon-adsystem.com/widgets/q?_encoding=UTF8&ASIN=B07JLJSDMJ&Format=_SL160_&ID=AsinImage&MarketPlace=JP&ServiceVersion=20070822&WS=1&tag=palibera-22&language=ja_JP" ></a><img src="https://ir-jp.amazon-adsystem.com/e/ir?t=palibera-22&language=ja_JP&l=li2&o=9&a=B07JLJSDMJ" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" />  

[am]: https://atom.io
[gh]: https://github.com
