# Gnuplot
## 1. 対話的に作成したグラフ

![force.png]

## 2. 関数のプロット
$y=sin(x)，tan^{-1}(x)$ のグラフを描く

```gnuplot {cmd=true output="html"}
set terminal svg

set title
plot sin(x),atan(x)
```
