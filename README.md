# Gumbel-max-trick

## Statement
<div align="left">
<img src="https://render.githubusercontent.com/render/math?math=\text{Assume that}\ \alpha_1, \alpha_2 ... \alpha_k\ \text{satisfy}\ \sum_k{\alpha_k} = 1.\ \text{Define}">
<p align="center"><img src="https://render.githubusercontent.com/render/math?math=Z = \arg\max_k\{{\log{\alpha_k}%2BG_k}\}"></p>
<img src="https://render.githubusercontent.com/render/math?math=\text{where}\ G_k, ..., G_n\ \text{i.i.d.}\ \sim\ Gumbel(0,1),\ \text{whose PDF and CDF are defined as}">
<p align="center"><img src="https://render.githubusercontent.com/render/math?math=f(x) = e^{-(x%2Be^{-x})}"></p>
<p align="center"><img src="https://render.githubusercontent.com/render/math?math=F(x) = e^{-e^{-x}}"></p>
<img src="https://render.githubusercontent.com/render/math?math=\text{.\ Then}\ \Bbb{P}(Z=k)=\alpha_k">
</div>

the expression refers to [here](https://www.hsfzxjy.site/2019-08-01-proof-of-gumbel-max-trick/)