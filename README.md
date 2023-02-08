# robosys2022のリポジトリ
・ロボットシステム学の2022年度授業の練習リポジトリ。
                            

## plusコマンド
![test](https://github.com/masasao/robosys2022/actions/workflows/test.yml/badge.svg)

・標準入力から読み込んだ数字の合計値を出すプログラムです。

```$ seq 数 | ./plus```

を行うと、 
{数+(数-1)+(数-2)・・・・・+2+1}
の計算ができます。
(数に0より小さい数字を入力すると計算結果は0になります。)
### 例
$ seq 5 | ./plus


↑(5+4+3+2+1=15)


## インストール方法
$ git clone https://github.com/masasao/robosys2022.git

$ cd robosys2022

を行ってください。

## 必要なソフトウェア
・ テスト済み   Python: 3.7〜3.10

## 動作確認済み環境
・Ubuntu18.04.5 Windows 
## ライセンス関係
・このソフトウェアパッケージは、3条項BSDライセンスの下、再頒布および使用が許可されています。


・このパッケージのコードは，下記のスライド（CC-BY-SA 4.0 by Ryuichi Ueda）のものを，本人の許可を得て自身の著作としたものです．

・[ryuichiueda/my_slides robosys_2022](https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022)


 * © 2023 masasao 
