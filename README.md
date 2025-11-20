# Causal Inference on UPI Cashback Scheme

## Project Overview
This project investigates whether UPI cashbacks genuinely increase user spending or merely redistribute transactions between platforms. Using advanced causal inference techniques on 5,000+ digital transactions, we provide empirical evidence on the true impact of cashback incentives.

## Quick Start
Simply run `Causal_inference.ipynb` - the notebook contains all data processing, analysis, and visualization steps in one integrated pipeline.

## Key Findings

### Causal Effects
- Cashbacks reduce transaction amounts by Rs. 1,500-3,700 per transaction
- Strong statistical significance (p < 0.001) across all methods
- Consistent negative effects across UPI, credit cards, debit cards, and wallets

### Platform Strategy Revealed
- Massive 57x difference in incentive rates: 287% for lowest spenders vs 5.8% for highest spenders
- High cashbacks target small transactions (Rs. 3,000 range)
- Minimal incentives on large transactions (Rs. 6,000+)

### Strategic Insight
Cashbacks function as acquisition tools rather than spend-boosting mechanisms - they drive user adoption and frequency but don't increase transaction sizes.

## Methodology
- Propensity Score Matching (PSM) for causal estimation
- Double Machine Learning (DML) for robustness validation  
- Causal DAGs with proper confounder identification
- Heterogeneous treatment effects by payment method

## Business Implications
- For Platforms: Continue cashbacks for new user acquisition, but don't expect spending increases from existing users
- For Regulators: Cashbacks expand digital payment adoption while requiring monitoring for predatory pricing
- For Merchants: Leverage cashback trends for targeted customer acquisition programs

---
## Contributors
- [Priyanka S](https://github.com/pris25123)
- [Padarthi Neha Sai](https://github.com/pnehasai)
- [Ritika Seth](https://github.com/ritikaseth1003)
- [Nityashree](https://github.com/Nitya1412)
