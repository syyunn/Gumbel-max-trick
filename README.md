# Gumbel-max-trick

## Statement

<img src="https://render.githubusercontent.com/render/math?math=\text{Assume that}\ \alpha_1, \alpha_2 ... \alpha_k\ \text{satisfy}\ \sum_k{\alpha_k} = 1.\ \text{Define}">
<p align="center"><img src="https://render.githubusercontent.com/render/math?math=Z = \arg\max_k\{{\log{\alpha_k}%2BG_k}\}"></p>
<img src="https://render.githubusercontent.com/render/math?math=\text{where}\ G_k, ..., G_n\ \text{i.i.d.}\ \sim\ Gumbel(0,1),\ \text{whose PDF and CDF are defined as}">


<!-- $$
\text{Assume that}\ \alpha_1, \alpha_2 ... \alpha_k\ \text{satisfy}\ \sum_k{\alpha_k} = 1.\ \text{Define}\\
Z = \arg\max_k\{{\log{\alpha_k}+G_k}\}\\
\text{where}\ G_k, ..., G_n\ \text{i.i.d.}\ \sim\ Gumbel(0,1),\ \text{whose PDF and CDF are defined as}\\
f(x) = e^{-(x+e^{-x})}\\
F(x) = e^{-e^{-x}}
.\ \text{Then}\ \Bbb{P}(Z=k)=\alpha_k
$$ -->
