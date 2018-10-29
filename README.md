﻿# MtgArenaJaCardViewer

![img01](https://raw.githubusercontent.com/WestHillApps/westhillapps.github.io/master/res/mtga-ja-card-viewer-icon.png)  
**Magic: The Gathering Arena（MTGA、MTG Arena、MTG アリーナ）**  
で日本語版のカード画像を表示するツールです。  
<br />
![img01](https://raw.githubusercontent.com/WestHillApps/westhillapps.github.io/master/res/mtga-ja-card-viewer-01.gif)  
<br />
## ダウンロード
* **[リリースページ](https://github.com/WestHillApps/MtgArenaJaCardViewer/releases)** から最新版の **MtgArenaJaCardViewer_vXXX.zip** を保存してください。  
<br />
## 使い方
* zipを解凍して **MtgArenaJaCardViewer.exe** を実行すると起動します。  
※MTGAを起動してから実行してください。  
※カード画像ダウンロードのために通信を行いますので、自己判断で通信許可をしてください。

* 終了するときは、タスクバーから右クリックで終了してください。  

* 画面上でマウスを止めた時に、近くのカード画像を解析して、日本語版のカード画像を表示します。

* スクリーン下部のチェックボックスで機能のON/OFFを切り替えられます。

* スクリーン下部のダイアログが回転している間は、画面の解析中です。  
<br />
## 仕様・機能
* **Windows10 64bit版** 専用です。

* 日本語版カード画像は初回表示時のみダウンロードされ、以下のフォルダに保存されます。  
**C:/Users/{ユーザー名}/AppData/LocalLow/WestHillApps/MtgArenaJaCardViewer/CardTextureCache/**  
※カード画像のダウンロード中は黒い半透明のカード枠が表示されます。

* 以下のカードには対応していません。  
**基本土地カード**  
**スタンダードフォーマット以外のカード**  
**MTGA専用カード、未発売のセット等の日本語版が存在しないカード**  

* カードによっては認識・マッチしない場合があります。  
対戦中にカードを右クリックすると画面左側に拡大画像が表示されるので、そちらだと認識しやすいです。

* カード以外の空間を誤認することがあります。

* **1920x1080**の画面サイズで動作確認しています。  
画面サイズは大きいほうが認識しやすいです。

* リアルタイムで画像解析を行っているため、**CPU負荷**はそれなりにあります。  
ある程度のスペックが無いと厳しいかも…

* 動作を改善していくために[Unityアナリティクス](https://unity.com/solutions/analytics)を使用しています。（[プライバシーポリシー](https://unity3d.com/legal/privacy-policy)）

* 開発中のため、不具合等色々問題あると思いますが、ご容赦ください。

* 何かあればTwitterアカウントへご連絡ください。  
どうしたら使いやすくなるのか模索中なので、ご意見募集中です！
<br />
<br />
## 連絡先
[@westhillapps](https://twitter.com/westhillapps)  

<a href="https://twitter.com/westhillapps">
<img alt="Follow me on Twitter"
src="https://raw.githubusercontent.com/WestHillApps/westhillapps.github.io/master/res/twitter.png" width="75"/>
</a>
<br />
<br />

## クレジット
以下のライブラリを使用しています。  
[MTG Developers SDK](https://magicthegathering.io/)  
[OpenCV for Unity](https://assetstore.unity.com/packages/tools/integration/opencv-for-unity-21088)  
[uWindowCapture](https://github.com/hecomi/uWindowCapture)  