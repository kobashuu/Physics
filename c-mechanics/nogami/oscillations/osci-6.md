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

# 振動
## 4.6 張力の限界値

<br>

微小部分について過程を使って微分方程式を立てようとして方針を見失った。
<br>
上と下で張力を区別して、境界条件としておもりの運動方程式を使うのが解説。賢い。
<br>
ここでも例に漏れず、釣り合いの式から変数を減らして、釣り合いの位置を原点として座標を設定し直す。そうすると、非斉次方程式になるので変分法を使って解く。
<br>
解説では導出済の公式を使っていたが、ここではゼロから導出した。
<br>
(*)という条件を勝手に課すことで定数が積分の形で求まる。
<br>
外力$fg\omega_0t $なので積の形になってるので部分積分を使って解く。
<br>
張力が求まれば、時間の関数として時間について評価する。
<br>


<img width="400" alt="rikigaku-89" src="./images/rikigaku-89.jpg">
<img width="400" alt="rikigaku-90" src="./images/rikigaku-90.jpg">
<img width="400" alt="rikigaku-91" src="./images/rikigaku-91.jpg">
<img width="400" alt="rikigaku-92" src="./images/rikigaku-92.jpg">

<br>
引っ張ったら大体反対向きに力かかるし、一般の強制振動の式めちゃくちゃ汎用性高くね？？？と思った。変分法でわりかし簡単に解けるし天才。