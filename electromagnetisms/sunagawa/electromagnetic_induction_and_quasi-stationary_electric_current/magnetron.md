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

# 電磁誘導と準定常電流
## マグネトロン

#### どういう現象

変動する磁場をかけて電子グルグルする。
<br>
いま、円筒座標系を考える。
<br>
電磁誘導の法則：$ \mathrm{rot} \mathbf{E} + \frac{ \partial \mathbf{B} }{ \partial t } = 0 $
<br>
から、変動する磁場は電場を作り出す。z軸方向に一定の磁場があるとすると、電場は$\varphi$方向、すなわち接線方向のみを持つ。
<br>
具体的な値を求める場合には積分形のほうがやりやすいという経験則から、
<br>
<br>
$ \oint_C E_{\varphi} ds = - \frac{d}{dt} \int_S B dS $
<br>
$ 2 \pi R E_{\varphi} = - \pi R^2 \frac{dB}{dt} $
<br>
$ E_{\varphi}(R) = \frac{1}{2}R ( - \frac{dB}{dt} ) $
<br>
<br>
電子は接線方向にこの大きさの電場をうけて加速する。
<br>
また、動径方向について遠心力が作用するが$B$は打ち消すように作用する。

<br>
<br>

####電子の運動方程式

接線方向：$ m\frac{dv(t)}{dt} = -eE_{\varphi}(R, t)$
<br>
動径方向：$ \frac{mv^2(t)}{r} = ev(t)B(R,t)$
<br>

#### 半径$r$を保ったまま運動する条件
