# TOYPRO-Question-Generator
## これは何
[トイプロ](https://app.toy-pro.net/ "TOYPRO Home")の問題を作成するための支援ツールです。

作成して直接アップロードするという機能は備えていません。
## 使い方
Python環境(3.6以降を想定)をインストールしている環境で実行してください。

このプログラムでは以下の編集ができます。

+ 作問者のアカウントのID
+ 問題のタイトル
+ 得点
+ タグ
+ 問題文
+ 必要な変数
+ 制約
+ テストケース(ランダムケースとコーナーケース)
+ 各テストケースに対する出力
+ 想定解のコード
+ ランダムなテストケースを生成するコード
+ 問題の解説文

また、GUI上に配置されたボタンを用いて以下のことができます。

+ 作成したjsonファイルから読み込む
+ 制約、必要な変数、指定した個数の入力例と出力例を問題文に追加する
+ テストケースを生成するコードから求めたテストケースを指定した回数生成する
+ テストケースと想定解から対応する出力を求める(出力欄の文字が消去されるのでご注意ください)
+ 作成した問題を保存する

また、以下のショートカットを用意しています。

+ Ctrl+s:jsonに保存する

## 注意点
~~誤ってウィンドウを閉じてしまった場合、保存するか確認する機能はついていません。この場合、データは失われます。~~ β18で改善済み
トイプロ側の仕様により、50KB以上のファイルはアップロードできません。

変数の名前を500文字以上にしないでください。システム変数と干渉する恐れがあります。
### 作成者
+ V.ll
