# RL-Crypto-Trading-Agent
A reinforcement learning agent that trades the same crypto universe used in the statistical arbitrage project.

## Key results:
~1.20 cost-adjusted Sharpe (~3x 0.46 cost-adjusted Sharpe in statistical arbitrage project)

## Dependencies:
python-binance, gymnasium, torch, pandas, numpy, matplotlib

## Project Summary:
This project builds a reinforcement learning trading agent in OpenAI Gymnasium, using PyTorch to implement PPO. Multiple training sessions produce Sharpe ratios consistently hovering around 1.20.

Intraday pricing data on 23 crypto assets was obtained from Binance; the assets are as follows: Bitcoin, Ethereum, Ripple, Solana, Binance Coin, Polkadot, Chainlink, Litecoin, Uniswap, Aave, Cardano, Avalanche, Dogecoin, Ethereum Classic, NEAR Protocol, Stellar, Bitcoin Cash, Sui, Artificial Superintelligence Alliance, Internet Computer, Render, Floki, and Shiba Inu.  The test data are the tickers' prices and returns from January 2024 to January 2025; the training data are the prices and returns from January 2019 to the end of 2023.
