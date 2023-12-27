# Heston Model

In the Heston Model, the volatility of the asset is a sotchastic process. The price of the asset is given by

$$ dS_t  = \mu S_t dt + \sqrt{V_t} S_t dW_t^S, $$

$$ dV_t = \alpha(b-V_t)dt + \sigma \sqrt{V_t} dW_t^V,  $$

and the correlation between the two Brownian motions is given by

$$ dW_t^S dW_t^V = \rho dt. $$

![plots](https://github.com/alexisdpc/Heston_model/assets/124795834/8c027d66-d434-4e33-9dbe-380885cea611)


The Cox-Ingersoll-Ross model for interest rates has the same equation as the volatility in this model. The former is used when interest rates are expected to remain always positive

$$ dr = \alpha(b-r)dt + \sigma \sqrt{r} dW_t. $$

The expectation and variance for the interest rate $r(t)$ correspond to 
\begin{align}
\mathbf{E}[r(t)] & = e^{-\alpha t} r_0 + b(1-e^{-\alpha t}) \nonumber \\[1ex]
%
{\rm Var}[r(t)] & = \frac{\sigma^2}{a} r_0 (e^{-\alpha t} - e^{-2\alpha t}) + \frac{b\sigma^2}{2\alpha} (1- e^{-\alpha t})^2 \nonumber 
\end{align} \\





