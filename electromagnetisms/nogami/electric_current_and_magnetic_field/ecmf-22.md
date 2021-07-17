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
## 3.22 放物線形導線の焦点上の磁束密度

めちゃくちゃ考えたけど結局$r$との外積がわかんなくていけなかったやつ。
<br>

焦点距離$r$が$ r = \frac{l}{ 1 + \cos \theta } $で書けるのを覚えていたのはエラい。(ただし今回は$ \theta $の取り方が違うので$ \frac{l}{ 1 - \cos \theta } $)
<br>
あと求めるのにめちゃくちゃ時間かけてたので、$ l = \frac{4a}{2} ,$焦点の座標$ (\frac{4a}{4}, 0) $になるのは覚えておきましょう。
<br>
<br>

$ ds \sin \phi = r d \theta $で書けるらしい。この近似思いつかんし図形的にも「ほんまか？？」って感じ。
<br>
<br>
まぁこれさえ手に入れば$ \mathrm{Biot-Savart} $の式にぶちこんで磁束密度をもとめれば一致する解を得ることができます。
<br>
<br>

<img width="400" alt="electromagnetism-130" src="./images/ecmf-22/Electromagnetism-130.jpg">
<img width="400" alt="electromagnetism-131" src="./images/ecmf-22/Electromagnetism-131.jpg">
<img width="400" alt="electromagnetism-132" src="./images/ecmf-22/Electromagnetism-132.jpg">