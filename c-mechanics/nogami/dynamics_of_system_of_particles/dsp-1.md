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

# 質点系の力学
## 5.1 質点系の角運動量 

重心系での(質量)x(座標)や運動量の和はゼロってことを使う。
<br>

<img width="400" alt="rikigaku-128" src="./images/dsp-1/rikigaku-128.jpg">
<img width="400" alt="rikigaku-129" src="./images/dsp-1/rikigaku-129.jpg">

<br>

慣性質量のお気持ちがわからん。
<br>
例えば、粒子2が拘束されてて$ \bm{r}_2 = 0, \bm{ \dot r} _2 = 0 $だった場合に
$$ \sum_{i} \bm{r}_i' \times m_i \bm{ \dot r}_i ' = m_1 ( \frac{ m_2 }{ m_1 + m_2 } )^2 \bm{r}_1 \times \bm{ \dot r } _1+ m_2 ( \frac{ m_1 }{ m_1 + m_2 } )^2 \bm{r}_1 \times \bm{ \dot r }_1 $$
$$ = \frac{ m_1 m_2 }{ m_1 + m_2 } \bm{r}_1 \times \bm { \dot r}_1 = \mu ( \bm{r}_1 \times \bm{ \dot r }_1 ) $$
動いてない粒子2の質量が全体の角運動量に出てくるの気色悪い。。

<br>