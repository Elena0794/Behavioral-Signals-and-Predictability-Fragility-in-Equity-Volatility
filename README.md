# Behavioral Signals and Predictability Fragility
### A Stability-Oriented Evaluation of Volatility Forecasting

Author: Elena Han

Motivation
----------
Financial markets exhibit strong volatility persistence.
While behavioral finance proposes mechanisms such as
overreaction, herding, and loss aversion, it remains unclear
whether such behavioral proxies provide incremental and
stable predictive content beyond simple autoregressive structure.

Research Question
-----------------
Do behavioral features contain incremental information about
volatility persistence after controlling for AR dynamics?
More importantly, is this information stable across time and assets?

Empirical Design
----------------
Baseline Model:
    Vol_t = f(Vol_{t-1})

Extended Model:
    Vol_t = f(Vol_{t-1}, Behavioral Proxies)

Evaluation Framework:
    - Rolling 250-day window   
    - Out-of-sample nested comparison    
    - Stability metrics (positive-ratio, CV)   
    - Cross-asset heterogeneity analysis   

Key Findings
------------
1. Incremental R² improvements are economically modest.
2. Overreaction exhibits persistent cross-window significance.
3. Signal stability varies substantially across assets.
4. Certain improvements appear regime-dependent.

Interpretation
--------------
Results suggest behavioral signals may reflect
state-dependent or fragile predictability,
rather than universally robust forecasting gains.

Implication
-----------
Emphasizing stability rather than point-estimate improvement
provides a more reliable assessment of behavioral predictability.

Next Steps
----------
- Structural break tests
- State-dependent coefficients
- Regime-switching specifications
- Larger cross-sectional validation
