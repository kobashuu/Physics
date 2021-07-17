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
## 3.1 正三角形コイルに作用するアンペールの力

#### ポイント

任意の閉回路について、回路の作る図形の面積を$S$、図形の平面に垂直に立てた単位法線ベクトルを$\mathbf{n}$として、
<br>
$ \mathbf{N} = IS \mathbf{n} \times \mathbf{B} $
<br>
このトルクはどこ基準でとってるんだっていうのは回路の端から端のトルクになる。トルクってか偶力ってことですね。理解。
<br>
<br>
紐があるならトルクはどこからとるんだよって思ったけど、紐との摩擦力が定義されていないので摩擦力ゼロ、すなわち紐の傾きないし存在は考えなくていいっぽい。なので天井から直接つるしたみたいな図を書きました。
<br>
<br>
閉電流のつくる図形の面積に、その平面に垂直に立てた単位ベクトル$ \mathbf{n} $と磁束密度$ \mathbf{B} $の外積をかけたやつが回路に作用するトルクになるので、トルクは回路平面上にあります。また、その大きさは傾きによって変わる。ので傾くほどトルクの水平成分は小さくなります。
<br>
それに対して傾くほど水平成分の大きくなる重力によるトルクとの釣り合いを調べるのが問題を解く方針。
<br>
<br>
正三角形の重心は頂点から$ \frac{a}{ \sqrt{3} } $のところにあり、その面積は$ \frac{ \sqrt{3} }{4} a $になります。覚えておくと便利そう。
<br>
<br>
<img width="400" alt="ecmf-1" src="./images/ecmf-2.jpg">