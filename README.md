# robosys2022
『ロボットシステム学』で使用しているリポジトリ

![test](https://github.com/MiyawakiKaito/robosys2022/actions/workflows/test.yml/badge.svg)

# ダウンロード方法
* http
```
https://github.com/MiyawakiKaito/robosys2022.git
```
* ssh
```
git@github.com:MiyawakiKaito/robosys2022.git
```
# コマンド
標準入力から読み込んだ数字を扱う

* seq 数 
  * 1から指定した数までを連続して出力する

## plusコマンド
標準入力から読み込んだ数字を足す

* 動作確認の例
```
seq <数字> | ./plus
```
## multiplyコマンド
標準入力から読み込んだ数字をかける

* 動作確認の例
```
seq <数字> | ./multiply
```

# 必要なソフトウェア・動作確認
* Python
  * Python3.7～3.10で動作確認済み
* Ubuntu
  * Ubuntu20.04で動作確認済み

# 著作権、ライセンス
  * このソフトウェアパッケージは，3条項BSDライセンスの下，再頒布および使用が許可されます．
* このパッケージのコードは，下記のスライド（CC-BY-SA 4.0 by Ryuichi Ueda）のものを，本人の許可を得て自身の著作としたものです．
  * [ryuichiueda/my_slides robosys_2022](https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022)

© 2022 Miyawaki Kaito

   
