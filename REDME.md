# Crypto Wallet Recovery Toolkit (Actual Version: BTC & ETC)

**For lawful, authorized wallet recovery and security demonstration purposes only.**

## Overview

This toolkit helps you interact with real BTC and ETC wallet addresses:
- Scan for addresses
- Check balances (BTC/ETC)
- Log recovery attempts to a SQLite database
- Transfer funds (with the correct private key and owner's permission)

**All actions must comply with local laws and ethical standards. NEVER attempt unauthorized access or use.**

## Usage

1. Ensure you have Python 3.8+ and install dependencies:
    ```bash
    pip install bitcoinlib web3 eth-utils requests
    ```

2. (Optional) Edit RPC URL for ETC node in the config section of `actual.py`

3. Run the main program:
    ```bash
    python actual.py
    ```

4. You will be prompted for:
    - Wallet type (BTC or ETC)
    - Wallet address (or scan simulation)
    - Transfer details (with real private key if doing actual transfer)

## SQLite Logs

All actions and balances are saved in `wallets.db` automatically for audit and transparency.

## Security

- **Private keys must be kept absolutely secure.**
- Only run on wallets you own or where you have documented permission.

## License

MIT
