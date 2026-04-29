# ROOJO Predictify - AI-Powered Decentralized Football Prediction Market

**A complete intelligent contract + tutorial for GenLayer**

This project demonstrates how to build a real-world decentralized prediction market using GenLayer's Intelligent Contracts. Users create markets for football matches, place bets, and the AI jury automatically resolves the outcome by fetching real data from the web.

## Technical Overview
- **Contract Type**: Python Intelligent Contract
- **Key Feature**: LLM Jury + web data fetching (no traditional oracles)
- **Deployed On**: GenLayer Testnet
- **Contract Address**: 0xfd188556eac4df7dd2a4246cddb6f61a154bfecb69aa4ea1771297443c96fa3c

## Tutorial: How to Build This Project Step by Step

### 1. Fork the Boilerplate
- Go to the official GenLayer boilerplate and fork it.

### 2. Open in GenLayer Studio
- Open `football_prediction_market.py`
- Customize the contract name and description

### 3. Deploy the Contract
- Fill constructor parameters (game date, team1, team2)
- Deploy → copy the contract address

### 4. Interact with the Contract
- Use `resolve()` method after the match ends
- AI jury handles everything automatically

## Why This Matters
GenLayer allows developers to build contracts that can reason about the real world. This prediction market is a perfect example of AI-native blockchain in action.

Full code and deployment screenshots are in this repository.

Built as an educational contribution for the GenLayer Builder Program.
