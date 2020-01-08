# Gumbel-max-trick

## Statement

$$
\text{Assume that}\ \alpha_1, \alpha_2 ... \alpha_k\ \text{satisfy}\ \sum_k{\alpha_k} = 1.\ \text{Define}\\
Z = \arg\max_k\{{\log{\alpha_k}+G_k}\}\\
\text{where}\ G_k, ..., G_n\ \text{i.i.d.}\ \sim\ Gumbel(0,1),\ \text{whose PDF and CDF are defined as}\\
f(x) = e^{-(x+e^{-x})}\\
F(x) = e^{-e^{-x}}
.\ \text{Then}\ \Bbb{P}(Z=k)=\alpha_k
$$

<script src='https://cdnjs.cloudflare.com/ajax/libs/mathjax/0.1/MathJax.js?config=TeX-MML-AM_CHTML'></script>
