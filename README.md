# MinecraftEnv
Minecraftサーバ inokinn.net にログインするための環境構築の手引きです。

___

# 手順

## Minecraft本体のインストール
- 公式からJava EditionをPCにインストールしてください。(Windows 10 Editionではダメです)
- インストールしたら、一度起動してアカウントの設定を行う。

## forgeのインストール
- 本リポジトリを clone もしくはダウンロードする。
- 本リポジトリ内の forge-1.12.2-14.23.2.2611-installer.jar を起動し、PCにインストールする。

## 起動オプションの設定
- Minecraftを起動し、起動オプションを開く。
- バージョンは release 1.12.2-forge-1.12.2-14.23.2.2611 を選択する。
- 複数の環境を併存させたい場合等、ゲームディレクトリは必要に応じて変更してください。
- 「プレイ」を押下してゲームを起動して、ゲームディレクトリ以下にmodsのフォルダが作られていることを確認してください。

## Modの配置
- 本リポジトリ内のmodsフォルダ以下にあるjarファイルを全て、ゲームディレクトリ/modsの中に入れる。

### Macで日本語入力できるようにする
- CocoaInput というModを導入します。
- http://forum.minecraftuser.jp/viewtopic.php?t=24394 から 「ダウンロードはこちらから」のリンク先に飛ぶ。
- CocoaInput-[1.9-1.12.2]-3.1.5.jar をダウンロードする。
- ダウンロードしたjarを ゲームディレクトリ/modsの中に入れる。

### 画面上にミニマップを表示したい時は(Optional)
- JourneyMap というModを導入します。
- https://minecraft.curseforge.com/projects/journeymap/files/2498312 から、「Download」ボタンを押下する。
- journeymap-1.12.2-5.5.2.jar をダウンロードする。
- ダウンロードしたjarを ゲームディレクトリ/modsの中に入れる。

## ゲームの起動
- 「ニュース」タブに戻り、先ほど設定した起動オプションを選択し、「プレイ」を押下。
- 「マルチプレイ」を選択し、「サーバーを追加」 -> サーバーアドレスに「inokinn.net」と入力し「完了」を押下。
- 追加したサーバを選択する。

___

# ログインできなくなった時は

## case 1 クライアント側のMODのバージョンが古い or MODが足りていない

サーバ側にMODを追加した際、ほとんどの場合クライアント側にも同じMODが入っていないとログインできません。<br>
本リポジトリを pull もしくはダウンロードしなおして、ゲームディレクトリ/modsの中に配置してください。

## case 2 「サーバーが閉鎖されました」のメッセージが表示され、追い出された

サーバの安定化のため、毎朝5:00にサーバアプリケーションの自動停止を行っています。<br>
5:01に再起動しますので、その後にログインしなおしてください。<br>
それ以外の場合、inokinnがサーバをメンテナンス中か、もしくはサーバアプリが落ちてしまっている可能性が高いです。<br>
告知なしにこの状態になっているのに気付いた場合はご連絡ください。

___

# 導入Modについて

| Mod名 | ファイル | 概要 | 解説リンク |
|:---|:---|:---|:---|
| Aether 2 | Aether-2-1.12.2.jar | 「天界」をモチーフとした新ディメンジョンを追加。 | `http://ramshome.blog.jp/archives/Arther-ii.html` |
| Biomes O' Plenty | BiomesOPlenty-1.12.2-7.0.1.2384-universal.jar | 新たに80個以上ものバイオームを追加。 | `https://lazysolomon.com/biomes-o-plentyで追加されるバイオーム/` |
| MrCrayfish’s Furniture Mod | cfm-4.2.0-mc1.12.2.jar | 大量の家具を追加。 | `http://minecraft-diary.jp/blog-entry-1223.html` |
| ChocoCraft Mod | ChocoCraft-Mod-1.12.1.jar | チョコボやギサールの野菜を追加。手懐けて名前を付けたり乗ったり交配させたり出来る。 | `http://vanya1o.blog.fc2.com/blog-entry-52.html` |
| Cosmetic Armor Reworked | CosmeticArmorReworked-1.12.2-v1.jar | ネトゲでありがちな、性能装備とは別に見た目装備を設定することが出来る機能を追加。防具非表示にも出来るので、オシャレが捗ります。 | `http://brokendisc.blog54.fc2.com/blog-entry-532.html` |
| Doomlike Dungeons | Doomlike-Dungeons-Mod-1.12.2.jar | 世界各地にダンジョンが追加される。 | `https://youtu.be/tSPC-mTrHYg?list=PLFJXfKtUiVHBX2Fcb1JrFffu7ymI2T5Le` |
| Electroblob's Wizardry | Electroblob's+Wizardry+-+4.1.1+-+MC+1.12.2.jar | 多数の魔法を追加。 | `https://www.youtube.com/watch?v=yWLPsxYBG7E` |
| Exotic Birds | Exotic-Birds-Mod-1.12.2.jar | 鳥のMOBを追加。 |  |
| IvToolkit | IvToolkit-1.12.jar | 何かの前提MOD。 |  |
| Ice and Fire | iceandfire-1.4.0-1.12.2.jar | 炎のドラゴンと氷のドラゴンを追加。また、世界各地にドラゴンの巣も追加される。 | `https://www.youtube.com/watch?v=_BbUKrRbzbI` |
| Iron Chests | ironchest-1.12.2-7.0.40.824.jar | 大容量チェストを追加。 | `https://ameblo.jp/aqzx/entry-11530145961.html` |
| iYAMATO's mod | iYAMATOs_mod_1.12.2-0.0.6.jar | 多数の武器種を追加。 | `http://zenkai-style.blogspot.jp/p/iyamatos-mod-1122.html` |
| JEI | jei_1.12.2-4.9.1.168.jar | 全アイテムのレシピを見ることができる。 | `https://muratcha.com/mod-just-enough-items-manual` |
| LLibrary | llibrary-1.7.9-1.12.jar | Mod用ライブラリ。Ice and Fireの前提MOD。 |  |
| Orbis API | OrbisAPI-1.12.2-1.0.2.jar | Aether 2の前提MOD。 |  |
| Quick Leaf Decay | QuickLeafDecay-MC1.12.1-1.2.4.jar | 木の幹を伐ったら葉っぱが散るようになる。 |  |
| Recurrent Complex | RecurrentComplex-1.4.7.jar | 世界各地にランドマークを生成。 |  |
| Ruins | Ruins-1.12.jar | 世界各地に遺跡を追加。 |  |
| SubLib | SubLib-1.12.2.jar | TelePadsの前提MOD。 |  |
| TelePads | TelePads-Mod-1.12.2.jar | テレポーターを追加。 |  |
| The Twilight Forest 〜黄昏の森〜 | twilightforest-1.12.2-3.6.345-universal.jar | 新ディメンジョン「黄昏の森」を追加。 | `https://milksalad.com/?p=654` |
