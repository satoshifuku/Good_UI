---
date: 2022-07-30T 14:13:26
layout: post
title: Semi-self Adjustment machine
subtitle: I don't know how to use the machine! I forget to take the change..." Here is a good news for you!
description: >-
image: assets/img/posts/Semi-self_Adjustment_machine/Semi-self_Adjustment_machine.jpg
optimized_image: assets/img/posts/Semi-self_Adjustment_machine/Semi-self_Adjustment_machine_resized_thumbnail.jpg
category: blog
tags: 
author: Keichi Hanada
paginate: false
---

## Semi-self Adjustment machine made by Teraoka

　最近、コンビニやスーパーなどのレジで、顧客自身が商品の登録から精算までを行う「セルフレジ」や、商品登録は店員が行い、精算は顧客自身が行う「セミセルフレジ」の導入が積極的に実施されている。セルフレジ導入の背景には、人件費の削減に加え、人手不足の解消を目指す狙いがある。
　セルフレジを利用したことがある人の中に、お釣りやレシートを取り忘れた、危うく取り忘れそうになった経験をしたことが一度はあるのではないかだろうか。「急いでいた」、「別の作業をしていた」など様々な要因があるかもしれないが、この失敗は人間の不注意だけなく、レジのデザインが悪かったために起きた失敗とも言える。
　今回紹介するレジは上記のミスを防ぐことに加え、初心者でも使いやすいレジのデザインとなっている。

## 物理的制約

レジの画面には、紙幣と硬貨を投入する場所がイラストで表示されている。実際にレジ画面の下側にはイラストと似たような場所があり、顧客はここにお金を投入することを理解できる。それに加え、投入口には紙幣と硬貨以外のモノが投入されにくい構造となっており、ここに物理的制約が存在していると考えられる。

## フィードバック

金額を投入すると、投入された金額がレジ画面に表示される。商品総額 > 投入金額の場合、「不足金額」が表示される。商品総額 <= 投入金額の場合、「お釣り」が表示されるため、120円入れたつもりが、実際は115円投入していたなどのうっかりミスに気づくことができる。

## インターロック

商品総額 > 投入金額の場合、次の「お釣りを発行する」という段階に進むことができないため、店側としてはレジの精算ミスを防ぐことができる。

## シグニファイア

このレジには、音と光のシグニファイアが存在する。金額を投入する際、紙幣と硬貨を投入する場所に青いランプが点滅する。この段階は「金額を支払う」フェーズであるため、顧客はそこにお金を投入することを理解することができる。また、「お釣りを発行する」段階では、お釣りが取られるまで高音が鳴り続け、お釣りが出る場所には赤い光が出続ける。「高音」や「赤色」は警告・危険というイメージがあるため、音と光のシグニファイアによって、顧客は自身の操作がまだ完了していないことを理解することができる。

## 記憶ラプスのスリップの防止

「代金の支払い」、「お釣りの受け取り」、「レシートの受け取り」の各段階でその作業が終わるまで次のステップに進むことができない。仮に、途中で電話がかかってきたり、別の作業をして、元の作業を忘れていたとしても、作業が完了するまで次のステップに進まないため、結果的にお釣りやレシートの取り忘れを防ぐことができる。
