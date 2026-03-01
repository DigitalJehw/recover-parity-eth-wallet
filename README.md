# Recover Your Old Parity/MEW Ethereum Wallet

Recover your wallet using just your Parity phrase, no seed phrase needed.

Based on this Reddit thread:  
https://www.reddit.com/r/ethereum/comments/bd5dys/restore_parity_wallet_from_mnemonic_option_not/

---

## Steps

1. Download [Fether Wallet](https://github.com/openethereum/fether/releases)
2. Use your Parity phrase to decrypt and load the account *(won't sync to mainnet — that's fine)*
3. Click the top right menu → **Backup Account**
4. Export the account's original JSON file and set a password
5. Save the JSON file
6. Open **MetaMask**
7. Import account → choose **JSON File**
8. Enter the password you just set
9. Done — your funds are accessible!

---

## Notes

- [MyEtherWallet v3.9.0](https://github.com/MyEtherWallet/etherwallet/releases/tag/v3.9.0)
  can decrypt the wallet with the Parity phrase but won't load ETH balance or
  connect to networks — that's why we use Fether as the middle step instead.
- Always do this on a secure, offline machine if possible.
- Never share your phrase, JSON file, or password with anyone.

---

## Disclaimer

This is provided as-is for educational purposes. Always verify steps independently before moving funds.
