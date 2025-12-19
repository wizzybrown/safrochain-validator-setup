# safrochain-validator-setup

This repository documents my deployment and configuration of a **Safrochain validator node**, set up using **Termius CLI** on a VPS. The purpose is to provide transparent proof of my technical contribution to the Safrochain ecosystem through validator infrastructure and network participation.

---

## 🔧 Environment Details

- **Blockchain:** Safrochain
- **Node Type:** Validator
- **Server Provider:** Racknerd VPS
- **Operating System:** Ubuntu 22.04
- **CLI Tool:** `safrochaind`
- **Access Tool:** Termius (SSH CLI)

---

## 🚀 Validator Setup Summary

The following steps were completed to deploy and activate the validator:

1. Installed the Safrochain binary
2. Initialized the node and configured chain parameters
3. Synced the node fully with the Safrochain network
4. Created validator keys and wallet
5. Submitted a `create-validator` transaction
6. Successfully bonded the validator to the active set

---

## 📊 Validator Information

- **Moniker:** BOBBY
- **Status:** BONDED (Active Validator)
- **Commission Rate:** 10%
- **Max Commission:** 20%
- **Identity:** onwuchurchill
- **Website:** https://github.com/wizzybrown

---

## 🖥️ Verification Commands

Validator status was verified using the following command:

```bash
safrochaind query staking validator addr_safrovaloper1yye2tzcq8tjnwwfuc8l2q4evn5l009zsrjk33c
