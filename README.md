
# 🛡️ Smart Contract Risk Analyzer

A data science project exploring opcode-level risk in Ethereum smart contracts using Python and the Etherscan API.

## 🔍 Overview

This project flags risky opcodes (`delegatecall`, `tx.origin`, `selfdestruct`, `callcode`) in verified smart contracts and uses risk scoring to identify potentially vulnerable contracts.

## 📊 Features

- Pulls verified contracts from Etherscan
- Flags opcode presence using Python
- Assigns risk scores and contract types
- Visualizes findings with seaborn/matplotlib
- Includes deep-dive writeups on Moonbirds, Azuki, and Gnosis Safe

## 📁 Project Structure

- `notebooks/` — data analysis + visualizations (Jupyter)
- `data/` — CSVs of contracts and risk scores
- `visuals/` — PNGs of charts
- `writeups/` — Notion-style reports

## 🧰 Tools Used

- Python 3, pandas, matplotlib, seaborn
- Jupyter Notebooks
- Etherscan API
- Excel (manual tagging)

## 📚 Writeups

- [Smart Contract Risk Analysis (Deep Dive)](https://www.notion.so/Smart-Contract-Analysis-1d4f4342442381cda2bbf67eee2a2364)
## 📜 License

MIT License
