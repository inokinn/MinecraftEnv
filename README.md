# MinecraftEnv
Minecraftサーバ inokinn.net にログインするための環境構築の手引きです。

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

### 画面上にミニマップを表示したい時は
- JourneyMap というModを導入します。
- https://minecraft.curseforge.com/projects/journeymap/files/2498312 から、「Download」ボタンを押下する。
- journeymap-1.12.2-5.5.2.jar をダウンロードする。
- ダウンロードしたjarを ゲームディレクトリ/modsの中に入れる。

## ゲームの起動
- 「ニュース」タブに戻り、先ほど設定した起動オプションを選択し、「プレイ」を押下。
- 「マルチプレイ」を選択し、「サーバーを追加」 -> サーバーアドレスに「inokinn.net」と入力し「完了」を押下。
- 追加したサーバを選択する。

# 導入Modについて
あとで書く
