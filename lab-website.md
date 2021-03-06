---
layout: post-labweb
title: 研究者・研究室のためのホームページ・ウェブサイト制作
date: 2019-10-02 10:00:00 +0900
last_modified_at: 2020-02-04 17:00:00 +0900
image: '/img/logo_labweb.png'
tags:
- laboratory
- website
description: 研究成果・最新情報などの発信の場としてのホームページ・ウェブサイトや個人のポートレートサイトを簡単に運営する方法をまとめました。研究者個人または研究室単位で情報を発信する手段と制作方法をウェブサイト・ホームページ制作初心者でもわかりやすく書いています。
---


---

発信の場としてのウェブサイト運営

## 研究活動×Web

研究者として活動するためには、経歴や業績、過去の学会発表などの「活動履歴」や、自分が行ったことのアウトリーチやこれから行うことの広報などの「活動内容」が評価の基準として付き纏います。近年では、Google ScholarやResearch Gateといった業績や職歴を整理することができる”研究者のためのツール”が広くに受け入れられ、自身の情報を発信することへのハードルが下がっています。また、一般の人たちと同じように、TwitterやFacebookなどのSNSを通して発信する研究者も多くみられます。研究者自身も他の研究者の情報を得ようとGoogle検索などの検索エンジンを使って、最新論文や所属の情報、連絡先を取得しようとすると思います。検索を行うときに最も信頼できる情報源は？と聞かれると、どのように答えるでしょうか。私自身の経験と周りの人たちから聞いた話を併せて考えると、最も信頼できる情報源は「所属機関のウェブサイト」だと思います。検索したい情報にもよると思いますが、所属機関のウェブサイト、特に所属している研究室のウェブサイトには最新の情報があるはずだと期待することでしょう。

---

## 研究室のウェブサイトを更新していますか？

しかし、研究室のウェブサイトの中には長い間更新されていなかったり、更新する権限の管理のために更新することが用意でなかったりする研究室を見たことがあります。古すぎて配置が崩れて見にくくなっているウェブサイトもあります。「ウェブサイトが存在さえすればいい」「最新の業績ならGoogle Scholarを見てくれ」。もちろん業績が豊富で知名度がある程度ある人はそれで十分でしょう。しかし、若い研究者や学生はどうでしょう。ウェブサイトに名前が掲載されていれば"このラボに所属しているんだ"というアイデンティティを示すことができます。それ以外の人でも、ウェブサイトがあると研究室という組織の存在や研究内容、メンバー、直近の出来事などをまとめて掲載することができ、SNSなどの用意されたツールとは一線を画することができます。

---

## 研究者個人のウェブサイトは必要か？

研究室の運営を行う立場の研究者でなければ、個人のウェブサイトを持つことも選択肢に入ります。研究室という枠に縛られず、自分自身を自由に発信することができる上、SNSなどのリンクを貼ったり、埋め込んだりすることも容易です。無料のウェブサイト作成ツールも多く、PowerPointやWordを使うくらいの感覚で簡単に作成することもできます。個人で情報を発信することにはそれなりのリスクが伴いますが、研究者としての業績などの情報を公開するだけであれば問題が起こることはまずないでしょう。ウェブサイトで研究成果を公開することは"アウトリーチ活動"にもつながるはずです。

---

## 研究集会の情報もウェブサイトへ

研究者が集まり研究成果を発表しあう研究集会を開催する機会も少なくありません。開かれた研究集会を企画する上で、ウェブサイトに情報を載せることは必須であると言っても過言ではありません。研究集会の情報を広く通知するだけではなく、その研究集会が開催された証拠もしくは履歴としての機能も有します。大きな学会の大会等であれば資金も豊富で制作会社に依頼することがほとんどかもしれませんが、小さな研究集会ではウェブサイト制作にかける予算が確保できない場合が多くあります。忙しい研究者は「研究集会のウェブサイトを作る時間なんてない」と思うかもしれませんが、開催情報を載せる程度であれば小一時間でウェブサイトを作成できるツールはたくさんあります。参加登録のためのフォームが欲しければGoogleフォームなどのフリーツールが使えます。短時間で研究集会のウェブサイトを作成する環境は揃っているのです。

---

## このページの目指すところ

このページにまとめる記事では、研究者が情報を発信する場としてのウェブサイトを作成する一連の流れや作成時のコツ、作成に使えるツールの紹介とその使い方、作成事例を紹介します。ウェブサイト作成の方法を知ることを通して、以下のことを目指します。

1. 研究者自身が簡単なウェブサイトを作成できるようになること
2. ウェブサイトの構成や掲載すべき情報を目的に応じて判断できるようになること
3. ウェブサイト制作に関して自分には何ができて何ができないのかを知ること

このページにまとめる記事では、ウェブサイト制作に関する詳細な知識を提供することを目的としません。ウェブサイトがどのように作られるかをある程度知ることができれば、情報発信の選択肢が広がります。また、ウェブサイト制作のテクニックは、プレゼンテーションのデザインにも応用がきき、研究者として知っておいて損はないはずです。無料で利用できるツールを中心に紹介するので、研究者個人に限らず小規模ビジネスなどにも役に立つ内容となっています。

---

### コンテンツ

{% for pages in site.categories.labwebsite %}
- [{{ pages.title }}]({{ pages.url }}) {% endfor %}

---

## このページを作成した理由

このページを作成した理由は２つあります。

一つ目は、管理者自身が研究集会などのウェブサイトを作成する機会と研究室のメンバーに作成方法を教える機会が多いからです。  
特に、全くウェブサイト制作をしたことがない人に教えるときは、一連の流れを一回で伝えることが難しく時間がかかってしまいます。ウェブサイト制作に関して検索したら出てくるような情報でも、ウェブサイトの目的に対して必要な情報はそれぞれなのでまとめたページが欲しかったのです。

二つ目は、管理者の母の会社「[株式会社かりえっと](https://calieto.com/)」の宣伝です。  
記事の中でリンクがたびたび出てくることがありますがお許しください。ただ、"このページの目指すところ"で書いた"3. ウェブサイト制作に関して自分には何ができて何ができないのかを知ること"について、ウェブサイトの作成方法を通してお伝えし、"できないこと"="ウェブ制作会社に任せた方が良いこと"として理解していただけたら幸いです。

{% include calieto.html %}
