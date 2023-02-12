# plusコマンド
![test](https://github.com/masasao/robosys2022/actions/workflows/test.yml/badge.svg)


・標準入力から読み込んだ数字の合計値を出すプログラムです。

`$ seq 数 | ./plus`

を行うと、 
{数+(数-1)+(数-2)・・・・・+2+1}
の計算ができます。  
(数に自然数以外を入力すると１と表示されます。)
### 例
`$ seq 5 | ./plus`  
`15`

↑(5+4+3+2+1=15)


## インストール方法
`$ git clone https://github.com/masasao/robosys2022.git`

`$ cd robosys2022`

を行ってください。

## 動作確認済み環境
・Python: 3.7〜3.10 テスト済み  
・Ubuntu18.04 Windows 
## ライセンス
・このソフトウェアパッケージは、3条項BSDライセンスの下、再頒布および使用が許可されています。


 * © 2023 masasao 
