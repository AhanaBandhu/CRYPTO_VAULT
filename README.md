# CryptoVault 🛡️  
**A Decentralized Financial Document Vault for Fraud-Proof Verification**

## 📌 Overview
CryptoVault is a **decentralized document management web application** that allows users to securely store, manage, and verify **receipts as well as critical financial documents** such as **insurance papers, bank checks, invoices, and reimbursement records** using **blockchain and IPFS**.

The project addresses real-world problems like **document loss, photoshopping, duplicate claims, and financial fraud** by ensuring that every uploaded document is **tamper-proof, immutable, and verifiable**.

---

## ❗ Problem Statement
- Financial documents like receipts, insurance papers, and checks are often **lost, damaged, or manipulated**
- Digital copies stored in drives or galleries can be **edited or photoshopped**
- Fake or inflated documents are frequently used for **insurance claims, reimbursements, and audits**
- Merchants and organizations lack a **trusted verification mechanism**

---

## ✅ Solution
CryptoVault solves these issues by:
- Storing **encrypted financial documents** on **IPFS**
- Recording only **cryptographic hashes and metadata** on the blockchain
- Using **wallet-based authentication (MetaMask)** instead of traditional logins
- Enabling **user–merchant verification** without exposing confidential document data

Any modification—even a single pixel—changes the document hash and **immediately detects tampering**.

---

## 🔄 Workflow
1. User connects their **MetaMask wallet** (wallet address acts as identity).
2. A document (receipt, insurance paper, check, invoice, etc.) is uploaded.
3. The file is **encrypted and stored on IPFS**, generating a unique **CID**.
4. The CID, hash, timestamp, and wallet address are stored via a **smart contract on Avalanche**.
5. A **SnowTrace transaction link** is generated for verification.
6. Merchants verify authenticity using the **hash or transaction link**, without accessing the raw document.

---

## ✨ Key Features
- 🔐 Wallet-based authentication (MetaMask)
- 📂 Secure storage for receipts and financial documents
- 🌐 Decentralized storage using IPFS
- ⛓️ Blockchain-backed immutability and transparency
- 🧾 Supports receipts, insurance papers, checks, invoices, and reimbursement documents
- 🔍 Merchant verification via blockchain explorer links
- 🚫 Prevents photoshopped, duplicate, or inflated claims
- 📸 Camera access to capture documents directly from the browser

---

## 🛠️ Tech Stack
**Frontend**
- HTML, CSS, JavaScript
- Camera APIs

**Blockchain & Web3**
- Solidity Smart Contracts
- Avalanche Blockchain
- MetaMask
- Ethers.js / Web3.js
- SnowTrace (Explorer)

**Storage**
- IPFS (Decentralized File Storage)

---

## 🏁 Conclusion
CryptoVault extends beyond simple receipt storage to become a **secure vault for financial documents**, ensuring authenticity, integrity, and trust. By combining **IPFS, encryption, and blockchain**, it enables fraud-proof verification while keeping sensitive information confidential and user-controlled.

📌 *Built as part of the Avalanche Hac*
