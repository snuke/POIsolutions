Rally 問題文 和訳
----

author: *snuke*

原文: [http://main.edu.pl/en/archive/oi/21/raj](http://main.edu.pl/en/archive/oi/21/raj)

（ストーリー略）

n 頂点 m 辺のDAGが与えられる。

１つ頂点を削除して、最長経路の長さを最短にしたい。

最適に削除した時の、最長経路の長さと、そのときに削除した頂点の番号を出力せよ。複数ある場合はいずれでも構わない。

###制約

2 ≦ n ≦ 500,000

1 ≦ m ≦ 1,000,000


###入力

```
n m
a_1 b_1
a_2 b_2
:
a_m b_m
```
頂点は1-indexed

###出力

削除すべき頂点の番号とそのときの最長経路の長さを空白区切りで。

###サンプル

######入力

```
6 5
1 3
1 4
3 6
3 4
4 5
```

######出力

```
1 2
```

