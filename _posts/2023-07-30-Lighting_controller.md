---
date: 2023-08-01T 12:00:00
layout: post
title: Lighting Controller
subtitle: Intuitive operation allows stress-free fine adjustment.
description: >-
image: assets/img/posts/Lighting_controller/Lighting_controller.jpg
optimized_image: assets/img/posts/Lighting_controller/Lighting_controller_resized_thumbnail.jpg
category: blog
tags: 
author: 甘夏
paginate: false
---

## 調色&調光専用リモコン（YRS-MCT-CNT）

色温度と明るさを細かく調節できる照明用コントローラ。電源ON/OFFの操作ボタン５つ、色温度調節（左右）のボタン２つ、明るさ調節（上下）のボタン２つ、の計9つのボタンがついており、中央に青く光るライトが内蔵されている。また、縦約110㎜・横約55㎜・高さ（厚み）約20㎜の大きさで、片手に収まるくらいのコンパクトなプロダクトであり、1部屋のメイン照明用コントローラとして使用している。

## 概念モデル（Conceptual Model）

ON/OFF の操作ボタンⅠ・〇 は、 電気信号の概念モデルから取られている。0/1 の電気信号は、電気通信における基礎概念であり、電圧が掛かっているときを「１」、電圧がゼロのときを「０」で表現する。


## 対応付け（Mapping）

・電源ボタン
電気信号の概念モデルが電源のON/OFFとして意味的に対応付けされており、OFFの（通電していない）状態が「〇」、ONの（通電している）状態が「Ⅰ」で表されている。

・4つの電源ボタン
リモコン下部にある４つのボタンの配置が4つのライトの位置に対応している。

・色温度調節ボタン
中央のサークル上にある左右のボタンで、段階的に色温度を調節することができる。右側のボタンを押すと昼光色になり、左側のボタンを押すと、電球色になる。これは、色温度を表すケルビン数と対応しており、値が大きいほど昼光色（青白い光）になり、値が小さいほど電球色（温かみのある光）になることと対応している。

・明るさ調節ボタン
中央のサークル上にある上下のボタンで、段階的に明るさを調節することができる。ここでは、上側のボタンを押すと明るくなり、下側のボタンを押すと暗くなる、という対応付けがされている。


## シグニファイア（Signifier）

・ボタンの位置と大きさ
コントローラの中央上部には、大きい「Ⅰ」と「〇」の２つのボタンが付いている。これは、これらのボタンで全体の調節ができることのシグニファイアとなっている。また、コントローラ下部の小さい４つのボタンは各照明と対応付けされており、各照明を調節できることのシグニファイアとなっている。
・ボタン上のラベル
ボタン上のラベルは「Ⅰ」「〇」「・」の3種類であり、これらは少なくとも３種類の操作ができることのシグニファイアとなっている。


## フィードバック（Feedback）

・青いライト
ボタンを押すと、リモコン中央の青いライトが光り、通電しているかどうかを確認することができる。
・操作時のクリック音
ボタンを押すと、カチッという音がし、ボタンを正しく押せているかどうか、音で確認することができる。


## 制約（restriction）

各ボタンは、「スイッチを押す」という行為によって作動するようになっている。そのため、間違って踏んだり、手が触れたりしても、作動しない。ボタンの押しにくさ（押すのに力がいること）は、物理的制約として機能している。