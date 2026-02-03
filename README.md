## Macro Data Forecasting & Diagnostic Framework (Python)
This project builds a time-series forecasting framework for tradable macroeconomic indicators (Unemployment rate from FRED) using autoregressive models.
### Objective
- Forecast macroeconomic data ahead of releases
- Evaluate forecast quality using information criteria
- Diagnose residual structure to ensure robustnessg
### Methodology
- AR models with multiple lag structures
- Model selection using AIC/BIC
- Residual diagnostics using Ljung–Box tests
- Forecast evaluation and interpretation
### Relevance
This framework mirrors the workflow used by macro research and portfolio management teams to monitor economic releases and assess their market impact.

Persistent autocorrelation patterns may indicate stable macro regimes, while breakdowns often coincide with policy shifts or economic shocks, making this framework useful for monitoring turning points relevant to rates and FX markets
