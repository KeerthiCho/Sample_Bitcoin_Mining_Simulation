# Sample_Bitcoin_Mining_Simulation
A Python script demonstrating the concept of **Proof-of-Work (PoW)** used in cryptocurrencies like Bitcoin.   This program "mines" by finding a hash with a given number of leading zeros — simulating how miners compete to solve computational puzzles.

## How It Works
1. Uses **SHA-256** hashing from Python's `hashlib` module.
2. Combines:
   - Block number
   - Transaction data
   - Previous block's hash
   - Incrementing nonce
3. Checks if the generated hash starts with a specific number of zeros (`difficulty`).
4. Stops when a valid hash is found.

## Features
- Adjustable mining difficulty  
- Simulation of the nonce incrementing process  
- Displays mining time and resulting hash  

## Requirements
- Python 3.x

## Usage
1. Save the script as `mining_simulation.py`
2. Run in terminal:
   ```bash
   python mining_simulation.py
  3. Adjust the difficulty variable in the code to increase/decrease mining time.**
