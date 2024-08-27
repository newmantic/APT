# APT

Arbitrage Pricing Theory (APT) is a multi-factor asset pricing model that explains the expected return of a financial asset based on its sensitivity to various macroeconomic factors. APT provides an alternative to the Capital Asset Pricing Model (CAPM) by allowing for multiple sources of systematic risk, rather than relying on a single market factor.


Expected Return (E(R_i)): The expected return of an asset is the return that investors anticipate receiving over a period, given the asset's exposure to various risk factors.

Risk-Free Rate (R_f): The risk-free rate is the return on an investment with zero risk, typically represented by government bonds like U.S. Treasury bills.

Factor Sensitivity (β_{ij}): Factor sensitivity (or factor loading) measures how much the asset's return responds to changes in a specific factor. Each asset has a beta coefficient for each factor, which represents its sensitivity to that factor.
β_{ij} = \text{Sensitivity of asset } i \text{ to factor } j


Risk Premium (RP_j): The risk premium associated with each factor is the additional return that investors require for taking on the risk associated with that factor.
RP_j = E(F_j) - R_f
Where:
E(F_j) is the expected return of factor j.
R_f is the risk-free rate.



The APT model expresses the expected return of an asset as a linear combination of the risk-free rate and the asset's sensitivities to various factors, each multiplied by its corresponding risk premium:
E(R_i) = R_f + β_{i1} \times RP_1 + β_{i2} \times RP_2 + \ldots + β_{in} \times RP_n
Where:
E(R_i) is the expected return of asset i.
R_f is the risk-free rate.
β_{ij} is the sensitivity (beta) of asset i to factor j.
RP_j is the risk premium associated with factor j.
n is the number of factors.



Factor Sensitivity (β_{ij}):
Each beta (β_{ij}) indicates how sensitive the asset's return is to changes in a particular factor. A higher beta for a given factor means that the asset's return is more sensitive to that factor's movements.

Risk Premium (RP_j):
The risk premium (RP_j) reflects the additional return required by investors for bearing the risk associated with factor j. The total expected return of the asset is adjusted by adding the contributions from all relevant risk factors.

No-Arbitrage Condition:
APT assumes that if an asset's price deviates from the price predicted by the model, arbitrage opportunities will arise, and traders will exploit these until prices adjust and the arbitrage opportunities disappear. This ensures that asset prices remain in equilibrium with their expected returns.
