# Numerical calculation of the Ionisation profile

$$\begin{equation}
\beta n_H^2 \alpha^2(x) = n_H(1-\alpha(x)) \int_{0}^{\lambda_{0}} \sigma(\lambda) \frac{I_\lambda(x)}{h\nu} d\lambda
\end{equation}$$

where 


- $\alpha(x)$ - ionisation fraction
- $\sigma(\lambda) = \sigma_0 (\lambda/\lambda_{0})^3$ - photoionisation cross-section
- $I_\lambda(x) = I_0(\lambda) e^{-\tau_\lambda(x)}$ - Intensity
- $\tau_\lambda(x) = \sigma(\lambda) \int_x^0 n_H (1-\alpha(x')) dx'$ - optical depth
