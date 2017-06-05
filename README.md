# Simplex_method
参考：http://www.mk-mode.com/octopress/2014/02/21/cpp-linear-programming-by-simplex/

最適解が存在しない場合にもループを停止する。

問題毎に修正が必要なのは、定数(#define)と係数行列のみ。

## simplex1.cpp
行列の行数が目的関数の変数の個数に満たない場合

## simplex2.cpp
Slack変数の最終解も求めたい場合（制約条件に目的関数に無い変数が含まれる場合）

## simplex3.cpp
最適解が存在しない場合
