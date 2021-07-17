<script type="text/javascript" async src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/MathJax.js?config=TeX-MML-AM_CHTML">

</script>

<script type="text/x-mathjax-config">
 MathJax.Hub.Config({
 tex2jax: {
 inlineMath: [['$', '$'] ],
 displayMath: [ ['$$','$$'], ["\\[","\\]"] ]
 }
 });
</script>

# 電流と磁場
## 3.11 有限長ソレノイドが中心軸上につくる磁場

#### 方針

円電流のつくる磁束密度の式を適切に座標をとって積分してやる。
<br>
<br>

#### ポイント

磁束密度のできる方向が最初間違えてたので気を付ける。外積なのでね。
<br>
まぁ本当に座標を正しくとってやることが一番大事。
<br>
三角関数で解いた方がいろいろ楽だったかもしれない。

<br>

$ \int \frac{1}{ (c + x^2)^{\frac{3}{2}} } = \frac{x}{c(c+x^2)^{\frac{1}{2}}} + C $
<br>
↑これはめちゃくちゃ使える。

<br>
<br>

#### 導出

<img width="400" alt="ecmf-9" src="./images/ecmf-9.jpg">
<img width="400" alt="ecmf-10" src="./images/ecmf-10.jpg">