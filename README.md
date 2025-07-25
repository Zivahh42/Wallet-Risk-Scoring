# Wallet Risk Scoring Project

## Description
This project scores DeFi wallets based on simulated Compound V2/V3 transaction activity. Each wallet is given a risk score between 0 and 1000.

## Features
- Simulated transaction data (transaction count, volume, risky interactions)
- Normalized feature scoring
- Weighted scoring logic
- CSV output of risk scores
- Optional visualization of score distribution

## Scoring Formula
`score = 0.4 * volume + 0.3 * transaction_count + 0.3 * risky_interactions (all normalized)`

## Output
- `risk_scores.csv`: Wallet ID and Score
- `score_distribution.png`: Histogram of score distribution (if run with visualization)
