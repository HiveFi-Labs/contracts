# HiveFi Contracts

This repository contains various smart contracts for the HiveFi project.

## Project Structure

- `ingredients/` - Implementation components for Solana's confidential transfer functionality
- `recipes/` - Test execution sequences for confidential transfers
- `utils/` - Utility functions

## Confidential Tokens

<img src="https://github.com/user-attachments/assets/02292d9c-1da1-492a-9bad-286698b59783" width="500" />

This is a token implementation utilizing Solana's confidential transfer functionality.
The repository implements confidential transfer flows similar to those found in the [Token Program CLI](https://github.com/solana-program/token-2022/tree/969cff212c0e0add812932e50f6771933f14ff5c/clients/cli).

## Setup

Follow these steps to set up the project:

1. Copy the `.env.example` file to `.env`
2. Edit the `.env` file as needed
3. Run `cargo build` 