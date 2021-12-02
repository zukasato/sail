# アプリ作成の流れ
## SET UP ワークスペースをセットアップする
### andoroid studioのダウンロード
https://developer.android.com/studio?hl=ja
### AVDの作成
android アプリを実行するための実機かAVDが必要
android studio内の[AVD Manager]から作成
### deveropersサイト
https://developer.android.com/studio/intro?hl=ja

## WRITE アプリを作成する
- 画面はXMLファイル（画面構成）+Kotolinクラス（処理）のペアで作られている
- メインで編集するファイルは
> res/layoutの.xml<br>
> javaの.kt<br>
> res/valueのstrings.xml<br>
> (アプリを多言語対応させるときに、別言語で記述したstrings.xmlを作成し所定のフォルダに入れておくことでAndroidOSで自動で言語を切替。同じ言葉を再利用するときにも便利)<br>
 
## Build and Run　ビルドして実行する
実行ボタン→エミュレーターで表示

## Publish　公開


# XMLファイル（画面構成）の作成
