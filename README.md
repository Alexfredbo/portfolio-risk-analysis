# Currency Risk Hedging at Sandvik

Does the choice of risk measure change the optimal hedging strategy?

Academic group project in Applied Corporate Finance, University of Copenhagen, June 2026.

## Overview

We examine how the choice between Value-at-Risk (VaR) and Expected Shortfall (ES) affects hedging decisions for Sandvik Group’s foreign-currency net assets.

The project connects quantitative risk modelling with a practical corporate treasury question: how much downside protection is worth paying for?

## Methods

- Python-based Monte Carlo analysis with 100,000 simulated scenarios over a one-year horizon.
- Gaussian and Student-t copula models to examine currency dependence and extreme outcomes.
- Comparison of VaR- and ES/CVaR-based hedge optimisation, incorporating forward hedging costs.
- Public exposure data from Sandvik’s 2025 Annual Report and historical exchange rates from the Swedish Riksbank.

## Key findings

The choice of risk measure affects hedge ratios most when hedging costs require trade-offs between protection and cost.

In one cost-sensitivity scenario, ES-focused optimisation retained 88% USD hedging where the VaR-focused strategy retained none. This provided greater protection against severe losses, but at a higher annual hedge cost.

The broader takeaway: risk measurement can influence financial decisions, rather than simply describe existing exposures.

## Limitations

Results are model-based, not realised outcomes. The analysis assumes fixed exposures and a static one-year hedge. Historical estimates may not capture future market conditions, and modelled hedging costs exclude dealer margins and other implementation costs.

## Authors

Alexander Fredbo-Nielsen, Emil Kjeldgaard Leth and Thomas Eisenhardt.

Individual contributions are documented in the report.

## Report

[Read the full report](Currency_risk_hedging_at_Sandvik.pdf)
