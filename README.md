<p align="center">
  <img src="BitSlowly.png" width="220" alt="BitSlowly Logo">
</p>

<h1 align="center">BitSlowly</h1>

<p align="center">
A CPU-Based Experimental Electronic Cash System
</p>

Introduction

BitSlowly is an experimental blockchain project designed to explore the implementation of a lightweight electronic cash system. The project focuses on simplicity, transparency, and educational value while implementing fundamental blockchain technologies such as Proof-of-Work, the UTXO transaction model, digital signatures, and peer-to-peer networking.

BitSlowly is developed as an independent research project and is intended for learning, experimentation, and continuous security improvement.

---

Features

- UTXO-based transaction model
- Proof-of-Work (PoW) consensus
- ECDSA (secp256k1) digital signatures
- Peer-to-peer (P2P) networking
- CPU mining
- Transaction validation
- Block validation
- Mempool management
- REST API interface
- Lightweight Python implementation

---

Project Structure

BitSlowly/
├── core.py
├── node.py
├── wallet.py
├── mining.py
├── consensus.py
├── ui py
├── docs/
│   ├── Whitepaper.pdf
│   ├── Bug_Bounty_Hunter_Part_I.pdf
│   └── logo.png
└── README.md

---

Quick Start

Clone the repository:

git clone <repository-url>
cd BitSlowly

Install dependencies:

pip install -r requirements.txt

Run a node:

python node.py

Run the wallet:

python wallet.py

Start mining:

python mining.py

---

Documentation

- 📄 BitSlowly Whitepaper
- https://drive.google.com/file/d/1-Ms9Xdgzm9ataCkj3m5_SJQCXkFaRZbQ/view?usp=drivesdk
- 🛡 Bug Bounty Hunter Part I
- https://drive.google.com/file/d/1pFpuY3N0DbZDRqkelurnXj3TnH5Y0S91/view?usp=drivesdk
- 📚 Project Documentation

---

Roadmap

- Improve peer-to-peer networking
- Enhance consensus mechanisms
- Expand security testing
- Optimize mining performance
- Improve wallet functionality
- Continue Bug Bounty Hunter research series

---

Project Status

BitSlowly is currently under active development.

New features, security improvements, and protocol refinements are continuously being implemented as part of the project's ongoing research.

---

Disclaimer

BitSlowly is an experimental software project developed for research and educational purposes. It should not be considered production-ready software or financial advice.

---

License

This project is released under the MIT License.
