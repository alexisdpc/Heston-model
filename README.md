# Heston Mode

The Heston Model models the volatility of the asset as a stochastic process. The price of the asset is given by

$$ dS_t  = \mu S_t dt + \sqrt{V_t} S_t dW_t^S, $$

$$ dV_t = \alpha(b-V_t)dt + \sigma \sqrt{V_t} dW_t^V,  $$

and the correlation between the two Brownian motion is given by

$$ dW_t^S dW_t^V = \rho dt. $$

![plots](https://github.com/alexisdpc/Heston_model/assets/124795834/8c027d66-d434-4e33-9dbe-380885cea611)



