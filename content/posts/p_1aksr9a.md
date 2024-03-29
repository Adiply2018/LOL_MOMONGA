---
title: 'パッチ14.03バグまとめスレ'
date: 1707509879
weight: 1
tags: ["LoL","hotから取得"]
categories: "LoL"
author: ["ZED-MOMONGA",]
draft: false
hidemeta: false
comments: false
description: 'パッチ14.03に関連する様々なバグの報告とその詳細。'
summary: 'パッチ14.03に関連する様々なバグの報告とその詳細。'
canonicalURL: "https://lolmomonga.net/posts/p_1aksr9a/"
searchHidden: false
ShowReadingTime: true
ShowWordCount: true
cover:
    image: "/images/i_1aksr9a.png"
    alt: ""
    caption: "" # display caption under cover
    #relative: true # when using page bundles set this to true
    hidden: false # only hide on current single page
    hiddenInSingle: false # hide on single page

---
**Nocturne@永遠の悪夢** <2024-02-07 12:01>  
召喚士ども、こんにちは！

Riotがチャンピオンやアイテムのバランスを取るために新しいパッチを導入するたびに、予期せぬ問題が発生してゲームプレイ中に混乱を引き起こすことがあります。これらの問題は最終的に修正されますが、パッチ直後にサブレディットがごちゃごちゃになることに気づきました。

これを避けるために、各パッチの後にメガスレッドを投稿し、そこでみんなが様々な問題を一箇所で報告できるようにしたいと思います。これにより、Riotはバグを簡単に追跡できる中心的なハブを提供し、他のユーザーも同じ問題に遭遇したかもしれないと確認できます。

**注：[14.3](https://www.leagueoflegends.com/en-us/news/game-updates/patch-14-3-notes/)パッチによって引き起こされたバグのみを以下に報告してください。**

バグを報告する前に注意すべき前提条件

***

1. バグは理想的にはスクリーンショットまたはビデオで添付されます。これにより、報告の信憑性が提供されます。
2. 可能であれば、バグを再現する手順を提出してください。これにより、Riotersはバグを再現し、その原因を見つけるのに役立ちます。
3. バグは最新のパッチによって引き起こされたものでなければなりません。

***

**バグを報告する際のフォーマット：** バグを報告する際には、コンピュータに関するできるだけ多くの情報を提供してください。

• **サーバー**：バグに遭遇したサーバー（NA、EUW、EUNE、TR、RU、BR、LAS、LANなど）

• **バグの種類**：クライアントバグ、ゲーム内バグなど

• **説明**：発生したバグを説明してください。

• **ビデオ/スクリーンショット**：バグが発生しているスクリーンショット（ゲーム内でF12）またはビデオを挿入してください。

• **再現手順**：他の人がバグを再現するために必要な手順を提供してください。

• **期待される結果**：上記の手順に従った場合の結果を記載してください。

• **観察された結果**：上記の手順に従った場合に得られた結果を記載してください。

• **再現率**：バグを再現しようとする場合、それが発生する成功率はどれくらいですか？（1/10：10回試して1回発生、5/10：10回中5回発生、10/10：毎回発生）

• **システムスペック**：プロセッサ、ビデオカード、RAM、HDD/SSD、ドライバーを含む、提供できるすべてのもの。

***

[**Redditでのコメントのフォーマットの仕方がわからない場合はこちらをクリックしてください**](http://www.reddit.com/r/leagueoflegends/wiki/formatting)

***

    - **サーバー：**   
    - **バグの種類：**   
    - **説明：**   
    - **ビデオ/スクリーンショット：**   
    - **再現手順：**   
    - **期待される結果：**   
    - **観察された結果：**   
    - **再現率：**   
    - **システムスペック：**  

上記のコードをコピーして貼り付け、詳細を記入してください。

***

このメガスレッドからバグのリストはスレッドのメインボディにまとめられずに投稿されますが、多くのRiotersがすべてのコメントを通して読んでいるので、1500番目や3000番目のコメントを投稿したとしても心配しないでください。次の数日間ですべての返信が読まれます。  

---

> 他サモナーの反応  

- **Samira@風の剣士** <2024-02-07 18:22>   
サーバー：EUW
バグの種類：クライアント/システムバグ
説明：Vanguardシステムチェックが機能していない
動画/スクリーンショットの挿入
再現率：10/10
再現手順：
クライアントを起動、右上の設定を押す、"一般>Vanguardシステムチェック"に行く、"互換性をチェック"ボタンを押す。
期待される結果：結果を伝えるメッセージボックスがポップアップする。
観察された結果：設定が閉じて、それ以上の情報なし。
システムスペック：Ryzen 3600X、Windows 11、Radeon RX 580  

  - **Gragas@酒豪戦士** <2024-02-07 23:01>   
  わかるわ。14.2でも同じことやってたわ  

  - **Senna@霊魂の射手** <2024-02-08 08:41>   
  PBEでしか動かんわ  

- **Ivern@森の友** <2024-02-07 22:38>   
サーバー：該当なし
バグの種類：クライアントバグ
説明：バンガードの互換性チェックが機能しない。ボタンをクリックすると設定ウィンドウが閉じるだけで、それだけ。
再現手順：設定を開く > 互換性チェックボタンをクリック > 設定ウィンドウが閉じて何も起こらないのを見る
期待される結果：システムが互換性があるかどうかを教えてくれるポップアップがあるはず
観察された結果：何もなし、文字通り何も起こらなかった
再現率：100%
システムスペック：Windows 10、3600x、6750XT、x570マザーボード、かなり標準的  

- **Jayce@未来の守護者** <2024-02-08 17:44>   
サーバー: NA
バグの種類: ゲーム内バグ（アイテム）
説明: ARAMのMalignanceがパッチノートのナーフと合ってないんだが（SRのMalignanceは60 + 5% AP表示；ARAMでは10 + .7% AP表示；パッチノートでは40 + 2.8% APって書いてある）
再現率: 10/10
再現手順: ARAMでアイテムをホバー/購入
期待される結果: パッチノート通り40 + 2.8% APになるはずだが、何かのステルスナーフがあったのか？
（Hubrisもステルスナーフされてるっぽい；キルごとに10 + 1になってるし、45秒間だけってなってる）
観測された結果: ARAMでのMalignanceのダメージが実質無に等しい
システムスペック: 該当なし  

  - **Lux@光の魔法使い** <2024-02-08 18:18>   
  わいも同じ問題持ってるわ  

    - **Leona@太陽の盾** <2024-02-09 01:41>   
    昨日も同じ問題をこのスレで報告したわ。まあ、俺のはアップボートされてないけどｗ  

- **Corki@老兵パイロット** <2024-02-09 19:55>   
サーバー：関係なし
バグの種類：ゲーム内
説明：Caitlynのパッシブのヘッドショットチャージが、EかWでヘッドショットした時になくなるようになった。4スタックでEかWでヘッドショットした場合、5回目のヘッドショットがスキップされる。パッシブのヘッドショットは、ワードや植物などを攻撃した時にも消費されるようになった。
ビデオ/スクリーンショット：後で追加する。
再現手順：パッシブを4または5スタックまでチャージし、罠やネットで捕まえたターゲットをヘッドショットする。
期待される結果：罠やネットで捕まえたターゲットをヘッドショットした後や、ワード、植物などを攻撃した後もパッシブが5スタックのまま残る。
観察された結果：パッシブのヘッドショットが補償なしで消費される。
再現率：100%。
システムスペック：関係なし。  

- **Kindred@死の二面性** <2024-02-07 21:50>   
サーバー：LAS
バグの種類：ショップ
説明：新シーズンからかな？他の言語の名前でアイテム検索できなくなったぞ
ビデオ/スクリーンショット：
再現手順：別の言語の名前でアイテムを検索する
期待される結果：以前のようにアイテムが表示される
観察された結果：ショップはサーバーの言語でのみ検索する
再現率：10/10
システムスペック：関係ない  

- **Urgot@恐怖の執行者** <2024-02-08 01:29>   
サーバー：NA
バグの種類：ゲーム内
説明：Brandのパッシブの燃焼効果（3回ヒットの爆発ではない）が、ダメージのティックが1より大きくない場合にダークハーベストを発動しない。他のDoT（ダメージ・オーバー・タイム）が1以下のダメージをティックごとに与える場合も同様に機能すると思われるが、他はテストしていない。このバグは何年も前から存在している可能性があるが、14.2でBrandのダメージティックレートが変更されたことで明らかになった。
ビデオ/スクリーンショット：https://streamable.com/cba1rn
再現手順：ターゲットのHPを50%以下にする。ダメージのティックが<1の場合、DHは発動しない。>1の場合、適切にDHが発動する。
期待される結果：DHが発動する
観察された結果：DHが発動しない
再現率：100%
システムスペック：関係なし  




[出典: Reddit](https://www.reddit.com//r/leagueoflegends/comments/1aksr9a/patch_1403_bug_megathread/)
