# robosys2022
・このリポジトリはロボットシステム学の2022年度授業の練習リポジトリです
。
・このリポジトリにはplusコマンドがあります。
## plusコマンド
![test](http://github.com/masanao/robosys2022/actions/workflows/test.yml/badge.svg)
・標準入力から読み込んだ数字の合計値を出すプログラムです。

$ seq 数 | ./plus

を行うと、 

数+(数-1)+(数-2)・・・・・+2+1

の計算ができます。

### 例

$ seq 5 | ./plus                                 
15


↑(5+4+3+2+1=15)



## 必要なソフトウェア
* Python
  * テスト済み: 3.7〜3.10

## テスト環境
* Ubuntu18.04.5 Windows 



 * © 2023 Masanao Hayashi 
