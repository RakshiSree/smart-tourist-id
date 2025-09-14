# smart-tourist-id
Blockchain contract for issuing and verifying tourist digital IDs
# 🌐 Smart Tourist ID – Blockchain Contract

This repository contains the Solidity smart contract for issuing and verifying Digital Tourist IDs using Blockchain. It is part of a larger project for **Smart Tourist Safety Monitoring & Incident Response System**.

## 📄 Smart Contract Overview

**Name**: `TouristID`

### 🔧 Functions

#### ➤ issueID(address user, string hash, uint startDate, uint endDate)
- Stores a tourist's digital ID hash with trip validity.
- Called when a tourist is registered.

#### ➤ verifyID(address user)
- Returns tourist’s `idHash`, `startDate`, `endDate`.

---

## 🧪 Deployment Info

- **Deployed Using**: Remix IDE
- **Blockchain**: Remix VM or Sepolia Testnet
- **Contract Address**: See `contract/address.txt`
- **ABI**: See `contract/abi.json`

---

## 📁 File Structure

