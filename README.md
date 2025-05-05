# Blockchain Core Concepts
This repository contains two educational simulations that illustrate fundamental blockchain principles using Python:
- Simple Blockchain Simulation ("TestCoin")
- Proof-of-Work (PoW) Mining Model

Together, they demonstrate core concepts such as SHA-256 hashing, block linking, nonce discovery, the avalanche effect, and blockchain immutability. Ideal for learning and experimenting with the foundations of blockchain technology.
##  Requirements
- Python 3 (compatible with Google Colab)
- hashlib (standard library)
- logging (standard library, used in PoW mining)
## 1. Simple Blockchain Simulation (TestCoin)
### Overview
Simulates a lightweight blockchain where each block:
- Contains a list of transactions.
- Includes the SHA-256 hash of the previous block.
- Demonstrates block chaining, integrity, and tamper detection.
### Features
- SHA-256 Hashing ensures that any small data change causes a drastically different hash (avalanche effect).
- Immutable Chain: Blocks reference previous hashes, making tampering detectable.
- Educational: Change one transaction and observe how all following hashes change.
### How to Use
- Open the notebook in Google Colab.
- Run each cell to simulate block creation.
- Try changing transactions to observe the avalanche effect.
## 2. Proof-of-Work (PoW) Mining Model
### Overview
Simulates the mining process by:
- Incrementing a nonce until a SHA-256 hash with a required number of leading zeros is found.
- Demonstrating real-world PoW concepts like mining difficulty and computational cost.
### Features
- Configurable Difficulty: Adjust the ZEROES constant to simulate harder mining.
- Nonce Discovery: Emulates how miners find valid hashes.
- Hash-Based Integrity: Highlights blockchain immutability through cryptographic hashing.
### How to Use
- Open the notebook in Google Colab.
- Run the cell to begin mining.
- Experiment by changing the block number, transactions, or previous hash.
## Avalanche Effect Demonstration
Both simulations showcase how even a minor change in input (e.g., modifying a transaction) results in a completely different hash — demonstrating the security and sensitivity of SHA-256 hashing used in real blockchain systems.
## Conclusion
This combined project provides an intuitive, hands-on understanding of:
- Blockchain structure and immutability
- SHA-256 hash behavior
- Proof-of-Work mining fundamentals

It serves as a great learning resource for students, educators, or developers entering the world of blockchain technology.
