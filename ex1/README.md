# computeCost.m
Please notice "h_func = X * theta;"
This line is about hypothesis function.

# gradientDescent.m
Please notice "theta = theta - 0.01 * (X') * (1/m) * (h_func - y);"
<script type="text/javascript" async src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-MML-AM_CHTML"> 
J = \frac{1}{2m}\left \| X\theta -y \right \|^{2}
=\frac{1}{2m}(X\theta -y)^{T}(X\theta -y)
=\frac{1}{2m}\left [ \theta ^{T}X^{T}X\theta -y^{T}X\theta -\theta ^{T}+y^{T}y \right ]
</script>
