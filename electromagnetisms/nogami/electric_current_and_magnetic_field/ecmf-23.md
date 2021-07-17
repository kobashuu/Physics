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
## 3.23 磁束密度の発散

$ \mathrm{div} ( \mathbf{A} \times \mathbf{B} ) = \nabla \cdot ( \mathbf{A} \times \mathbf{B} ) = \mathbf{A} \cdot ( \mathbf{B} \times \nabla ) =  - \mathbf{A} \cdot ( \nabla \times \mathbf{B} ) = - \mathbf{A} \cdot \mathrm{rot} \mathbf{B} $
<br>
みたいな公式があって、覚え方は一個ずつずれるやつ。
<br>
<br>
これを使って$ \mathrm{Biot-Savart} $から導くのが正規で天才的な発想でベクトルポテンシャルを導いて発散を計算するのは丸ではないです。
<br>
<br>

<img width="400" alt="electromagnetism-133" src="./images/ecmf-23/Electromagnetism-133.jpg">