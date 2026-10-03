## 💸 Fintech POO + Blockchain Challenge

> A secure fintech wallet with immutable transaction history powered by a custom blockchain implementation. Built with OOP principles.

**Live Demo:** https://moralesensuecia.github.io/fintech-poo-blockchain/
**Author:** LuksMor - 2026

### 🚀 What is this?

This is not just another CRUD wallet. It's a **Fintech System** designed under **Object-Oriented Programming (POO)** principles where every financial movement is secured by a **Blockchain**.

Each `BankAccount` owns its own `Blockchain`, and every `DEPOSIT` / `WITHDRAW` creates an immutable `Block` linked by cryptographic hashes.

If someone tries to tamper with the history, the chain breaks. And we can prove it.

### 🧠 POO Architecture

**Principles:** Encapsulation, Abstraction, Unique CTA constraint.

### ⛓️ Blockchain Features

- **Genesis Block:** Every account starts at #0
- **Immutable Ledger:** Full history with hash and prevHash
- **Balance Tracking:** Each block stores balanceBefore / balanceAfter
- **Verification:** Verify Blockchain checks integrity
- **Fraud Simulation:** Simulate Hack tampers Block #1 to show `CORRUPTED`

**Fraud demo:**
1. Click `Simulate Hack` -> amount becomes $999999
2. Click `Verify` -> `CORRUPTED: Block #2 prevHash mismatch`
3. Proves immutability.

### 💻 How to Use

1. Register (Name, DNI, Email, Pass)
2. Create Account (Unique CTA code + initial balance)
3. Operate (Deposit/Withdraw)
4. Audit (Check history + Verify)

Data persists in localStorage.

### 📦 Stack
Vanilla JS, HTML5/CSS3, GitHub Pages, Custom btoa() hash

### 👨‍🏫 For the Professor
- POO modeling
- Account management
- Transaction logic
- **Desafío Blockchain:** hash linking, validation, fraud detection [x]

---
Made in Bålsta, Sweden by LuksMor.
