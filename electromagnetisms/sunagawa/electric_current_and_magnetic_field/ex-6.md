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
## 例題6 閉電流と磁気双極子

#### 結論

磁気双極モーメントベクトル： $ \mathbf{m} = \mu_0 I \cdot \frac{1}{2} \oint_C ( \mathbf{s} \times d\mathbf{s} ) $
<br>
$ \mathbf{A} (\mathbf{r}) = \frac{ 1 }{ 4\pi } \frac{ \mathbf{m} }{ r^3 } $
<br>
$ \mathbf{B} (\mathbf{r}) = \frac{ 1 }{ 4\pi } [ \frac{\mathbf{m}}{r^3} + \frac{ \mathbf{r} \cdot ( \mathbf{m} \cdot \mathbf{r} ) }{r^5} ] $
<br>
$ \mathbf{H} (\mathbf{r}) = \frac{ 1 }{ 4\pi\mu_0 } [ \frac{\mathbf{m}}{r^3} + \frac{ \mathbf{r} \cdot ( \mathbf{m} \cdot \mathbf{r} ) }{r^5} ] $
<br>
<br>

#### 方針
一般の閉電流のつくるベクトル・ポテンシャルを磁気双極子モーメントに置き換えるところからスタートする。
<br>
<br>

#### 導出

<img width="400" alt="ex-1" src="./images/ecmf-17.jpg">
<img width="400" alt="ex-1" src="./images/ecmf-18.jpg">
<img width="400" alt="ex-1" src="./images/ecmf-19.jpg">