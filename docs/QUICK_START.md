# 🚀 Quick Start - Allianza Blockchain

Quick guide to get started with Allianza Blockchain.

---

## 📋 Prerequisites

- Python 3.8+
- Node.js 14+ (for JavaScript SDK)
- Git

---

## 🔧 Installation

### 1. Clone the repository

```bash
git clone https://github.com/dieisonmaach-lang/allianzablockchainpublic.git
cd allianzablockchainpublic
```

### 2. Install Python dependencies

```bash
pip install requests
```

### 3. Install JavaScript SDK (optional)

```bash
npm install allianza-qss-js
```

---

## 🏃 Getting Started

### Option 1: Use the Testnet API

The easiest way to get started is using our public testnet:

```javascript
// JavaScript/TypeScript
import QSS from 'allianza-qss-js';

const proof = await QSS.generateProof('bitcoin', 'your_tx_hash');
console.log('Proof Hash:', proof.proof_hash);
```

### Option 2: Run Examples

```bash
# QSS Demo
python examples/qss_demo.py

# QRS-3 Demo
python examples/qrs3_demo.py

# ALZ-NIEV Demo
python examples/alz_niev_demo.py

# Interoperability Demo
python examples/interoperability_demo.py
```

### Option 3: Run All Tests

```bash
python tests/run_all_demos.py
```

This will run all demos and generate a complete report.

---

## 🌐 Testnet

Access our public testnet: **https://testnet.allianza.tech**

- ✅ Faucet for testing
- ✅ Block explorer
- ✅ QSS API endpoints
- ✅ Developer Hub
- ✅ Leaderboard

---

## 📚 Documentation

- [API Reference](API_REFERENCE.md)
- [CLI Usage Guide (Windows)](CLI_USAGE_GUIDE_WINDOWS.md)
- [QSS for Other Blockchains](../QSS_FOR_OTHER_BLOCKCHAINS.md)
- [Whitepaper](../WHITEPAPER_ALLIANZA_BLOCKCHAIN.md)

---

## 🔗 Useful Links

- **Testnet**: https://testnet.allianza.tech
- **Developer Hub**: https://testnet.allianza.tech/developer-hub
- **npm SDK**: https://www.npmjs.com/package/allianza-qss-js
- **GitHub**: https://github.com/dieisonmaach-lang/allianzablockchainpublic

---

## ⚠️ Important Note

This repository contains **public-facing code and documentation only**. The core blockchain implementation remains private for security reasons.

---

**Built with ❤️ for the post-quantum future**
