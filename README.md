## futaba favicon changer
このUserscriptはふたば☆ちゃんねるのレスページのファビコンをスレ画像に変更します。  

Firefoxの場合、[Tampermonkey](https://addons.mozilla.org/ja/firefox/addon/tampermonkey/)を先にインスールしてからスクリプトをインストールして下さい。  
(GreasemonkeyやViolentmonkeyでの動作は未確認です)  
Chromeの場合、[Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo/)を先にインスールしてからスクリプトをインストールして下さい。  

※このUserscriptは単体で利用可能ですが、Firefoxアドオン[KOSHIAN](https://addons.mozilla.org/ja/firefox/user/anonymous-a0bba9187b568f98732d22d51c5955a6/)（改変版含む）との併用も可能です。ふたば用アドオンの[赤福Firefox SP](http://toshiakisp.github.io/akahuku-firefox-sp/)・[ふたクロ](http://futakuro.com/)・[五平餅](https://toshiaki-gohei.github.io/gohei-mochi/)には同等の機能が実装されているので本スクリプトは不要です。  
※その他のUserscriptとFirefoxアドオンKOSHIANの改変版は[こちら](https://github.com/akoya-tomo/futaba_auto_reloader_K/wiki/)の一覧からどうぞ

## インストール
[GreasyFork](https://greasyfork.org/ja/scripts/39342-futaba-favicon-changer/)　
[GitHub](https://github.com/akoya-tomo/futaba_favicon_changer/raw/master/futaba_favicon_changer.user.js)

## 設定
機能の動作はスクリプト冒頭の大文字変数をエディタで編集すれば変更することができます。  

* USE\_CATALOG\_THUMBNAIL :カタログのサムネ画像を使用する（デフォルト：true）  
  - ファビコンにカタログのサムネ画像を使用します。（KOSHIAN Favicon Changerと同じ動作）  
    falseに設定するとスレのサムネ画像を使用します。ファビコンの表示にほとんど差はありませんが、[futaba auto reloader K](https://greasyfork.org/ja/scripts/36235-futaba-auto-reloader-k/)の通知アイコンのサイズが変化します。  

## 注意事項
* このUserscriptは現在非公開になっているFirefoxアドオンKOSHIAN Favicon Changerの代替として作成されたものです。既にKOSHIAN Favicon Changerをインストールしている場合は本スクリプトは不要です。  

## 更新履歴
* v1.0.0 2018-03-09
  - 新規リリース
