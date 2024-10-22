# TON Wallet Generator

This script generates multiple TON blockchain wallets and saves their addresses and private keys to a file.

## Features

- Generates wallets in the TON blockchain
- Saves wallet addresses and private keys to a text file
- Includes a progress bar to monitor the generation process

## Requirements

- Python 3.x
- `tqdm` library for the progress bar
- `tonsdk` library for interacting with TON wallets

## Installation

1. Clone the repository:

   ```
   git clone https://github.com/flaming-chameleon/ton-wallet-generation.git
   cd ton-wallet-generation
   ```

2. Install the required libraries:
   ```
   pip install -r requirements.txt
   ```

## Usage

1. Run the script:

   ```
   python ton_wallet.py
   ```

2. Enter the number of wallets to generate when prompted.

The generated wallet addresses and private keys will be saved in the `wallets.txt` file.