<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=default"></script>
# Linear Models

## Linear Models for Regression

这一主题是线性回归，即通过学习给定的样本数据获得一个回归函数，来刻画输入与输出的关系，所谓线性是指，函数的形式是输入的线性组合。具体而言：

- 输入数据的直接线性组合：$$h_\theta(x)=\sum_{i=0}^n \theta_i x_i =\theta^Tx$$

- 输入数据的非线性函数的线性组合：$$h_\theta(x)=\theta_0 + \sum_{j=1}^{M-1} \theta_j \phi_j(x)$$
