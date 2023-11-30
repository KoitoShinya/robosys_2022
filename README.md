# plusコマンド
![test](https://github.com/koitoshinya/robosys_2022/actions/workflows/test.yml/badge.svg)

標準入力から読み込んだ数字を足す。（整数に限る。）

## 実行例と結果
下記のコマンドは生成した、連続した整数を足し合わせて出力するというものである。
seq 5の場合は１～５までを、seq 10の場合は１～１０まで生成した、連続した整数を足し合わせる。
```bash
seq 5 | ./plus
15

seq 10 | ./plus
55
```
## インストール
下記を実行するとリポジトリがクローンされる。
```bash
git clone git@github.com:KoitoShinya/robosys_2022.git
```

## 必要なソフトウェア
* Python
* テスト済み: 3.7～3.10

## テスト環境
* Ubuntu 20.04 on Windows

## ライセンス
* このソフトウェアパッケージは，3条項BSDライセンスの下，再頒布および使用が許可されます．
 * このパッケージのコードは，下記のスライド（CC-BY-SA 4.0 by Ryuichi Ueda）のものを，本人の許可を得て自身の著作としたものです．
    * [ryuichiueda/my_slides robosys_2022](https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022)                              [ryuichiueda/my_slides robosys_2022 lesson4.md](https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022/lesson4.md)　
* © 2023 Shinya Koito

