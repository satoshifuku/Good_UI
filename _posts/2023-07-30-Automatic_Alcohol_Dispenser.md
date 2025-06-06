---
date: 2023-08-01T 12:00:00
layout: post
title: Automatic Alcohol Dispenser
subtitle: Know what to do at a glance
description: >-
image: assets/img/posts/Automatic_Alcohol_Dispenser/Automatic_Alcohol_Dispenser.png
optimized_image: assets/img/posts/Automatic_Alcohol_Dispenser/Automatic_Alcohol_Dispenser_resized_thumbnail.png
category: blog
tags: 
author: n
paginate: false
---

## tette TE500

これは、建物の出入り口等に置かれることのある自動式アルコールディスペンサである。
下部にアルコールのタンクがあり、上部にはセンサーや噴射機構がある。そこからアルコール噴射ノズルが突き出ている形状である。
ノズルの下に手をかざすことでセンサーが反応し、下部のタンクからアルコールを吸い上げ手に噴射し、手を消毒することができる。

## 概念モデル

この形が概念モデルとなっている。
なぜならば、ハンドソープや手動式アルコール、シャンプーといった手に何かを出すための容器は下にタンク、上に押す部分があり、突き出しているノズルから内容物が出てくるという共通点を持っている。
この製品も自動式ではあるが似たような形を取ることで、見ただけでノズルから何かを出すものだと分かるからである。
また、受け皿もこれが何かを噴射する機器だということを説明する概念モデルになっていると言える。

## 論理的制約

形から何をする機器なのかは分かったが、手動式なのか自動式なのかは分からない。
しかし、機器の上部が平らになっていて押すものがないことから論理的制約により、この機器は自動式でノズルの下に手をかざすだけで良いということが分かる。
また、押す場所がないために機械に対して可能な操作に制限がかかるという意味では、物理的制約とも言える。

## シグニファイヤ

タンクが半透明になっていることがアルコール残量を示すシグニファイヤとなっており、ユーザーは蓋を開けずにアルコール残量を確認できる。

## フィードバック

手をかざすとプシュッと音を立てアルコールが噴射されることが手をかざしたことに対するフィードバックとなっており、正しく噴射され手を離しても良いことが分かる。
また、アルコール切れの場合、半透明なタンクは残量がないことを示すことで噴射が行われなかったことに対するフィードバックとなっている。