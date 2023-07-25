- ***1st stage***: regress n on z
    get the prediction $x^n = x^n_0 + x_1^nz$
- ***2nd stage***: regress $y$ on $\hat{x}$
    get unbiased estimate on $\hat{\beta_0}$ & $\hat{\beta_1}$
    
Assume $x_0$ and $x_1$ were known;
What coeffcient do we obtain if we regress $y$ on $(x_0+x_1z)$
$$
Y_I = \beta_0 + \beta_1x_1 + Ɛ_1$$

$$
= \beta_0+\beta_1(x_0+x_1z_1 + v_i)+Ɛ_i$$

$$= \beta_0 + \beta_1\underbrace{(x_0+x_1 z_i)}_{$z_i} + \underbrace{\beta_1v_i + Ɛ_i}_{e_i}$$

$$ y_i = \beta_0+\beta_1z_i + e_i$$



![](https://hackmd.io/_uploads/r1TRUYh52.png)
![](https://hackmd.io/_uploads/SyIgPth93.png)


![](https://hackmd.io/_uploads/HyDOmFhcn.png)


Useful Resources:
https://hackmd.io/@yueswater/instrument_variable