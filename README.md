# 🗳️ Decentralized Voting System Using Blockchain

A blockchain-based **Decentralized Voting System** designed to provide a transparent, secure, and tamper-resistant voting process using **Ethereum, Solidity, Web3, and MetaMask**.

This project was developed as an academic and collaborative Blockchain project to demonstrate how decentralized technologies can be applied to digital voting systems.

---

## 📌 Project Overview

Traditional voting systems can face challenges related to transparency, centralized control, data integrity, and trust.

This project explores a decentralized approach where voting operations are managed through **blockchain smart contracts**. Votes can be recorded and verified on the blockchain, reducing dependence on a centralized authority.

### Key Objectives

* 🔐 Improve voting security
* 🌐 Use blockchain for decentralized vote management
* 🔎 Provide greater transparency
* 🛡️ Prevent unauthorized modification of recorded votes
* ⚡ Demonstrate smart-contract-based voting
* 🦊 Integrate MetaMask for blockchain interaction

---

## ✨ Features

* 👤 Voter registration and management
* 🗳️ Candidate-based voting
* 🔐 Blockchain-based vote recording
* ⛓️ Ethereum smart contract integration
* 🦊 MetaMask wallet integration
* 📊 Vote counting and result display
* 🔎 Transparent transaction verification
* 🌐 Web-based voting interface
* 🧪 Local blockchain testing with Ganache
* 🚀 Support for Ethereum test networks such as Sepolia

---

## 🛠️ Technologies Used

| Technology       | Purpose                                |
| ---------------- | -------------------------------------- |
| **Solidity**     | Smart contract development             |
| **Ethereum**     | Blockchain network                     |
| **Web3.js**      | Blockchain interaction                 |
| **MetaMask**     | Wallet and transaction management      |
| **JavaScript**   | Application logic                      |
| **HTML5**        | Frontend structure                     |
| **CSS3**         | Frontend styling                       |
| **Node.js**      | Backend/runtime environment            |
| **MySQL**        | Data management                        |
| **Ganache**      | Local blockchain development           |
| **Sepolia**      | Ethereum test network                  |
| **Git & GitHub** | Version control and project management |

---

## 🏗️ System Architecture

```text
                    ┌─────────────────────┐
                    │       Voter         │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │   Web Application   │
                    │    HTML/CSS/JS      │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │      MetaMask       │
                    │   Wallet / Web3     │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │ Ethereum Blockchain │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │  Solidity Smart     │
                    │     Contract        │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │ Voting Records &    │
                    │      Results        │
                    └─────────────────────┘
```

---

## 🔄 How the System Works

### 1. Connect Wallet

The voter connects their **MetaMask wallet** to the application.

### 2. Voter Registration

Eligible voters are registered through the application's voting system.

### 3. Candidate Selection

The voter can view the available candidates and select their preferred candidate.

### 4. Cast Vote

The voting transaction is sent through MetaMask and processed by the Solidity smart contract.

### 5. Blockchain Verification

The transaction is recorded on the Ethereum blockchain, providing a transparent and tamper-resistant record.

### 6. Vote Counting

The smart contract maintains the voting data and the application displays the corresponding results.

---

## 📂 Project Structure

```text
Decentralized-Voting-System/
│
├── contracts/
│   └── *.sol
│
├── frontend/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
├── backend/
│
├── migrations/
│
├── images/
│
├── README.md
│
└── package.json
```


---

## ⚙️ Installation & Setup

### Prerequisites

Make sure the following are installed:

* Node.js
* npm
* MetaMask
* Git
* Ganache or access to an Ethereum test network

Check Node.js:

```bash
node --version
```

Check npm:

```bash
npm --version
```

Check Git:

```bash
git --version
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Dhruvchain/Decentralized-Voting-System.git
```

Move into the project:

```bash
cd Decentralized-Voting-System
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start your local blockchain

Open **Ganache** and create/start a local blockchain network.

### 4. Configure MetaMask

Connect MetaMask to your selected blockchain network and import the required development account if using Ganache.

### 5. Deploy the smart contract

Compile and deploy the Solidity smart contract according to the project's configuration.

### 6. Start the application

Use the appropriate project command, for example:

```bash
npm start
```

or run the frontend through your configured development environment.

---

## 🧪 Testing

The application can be tested using:

* Ganache for a local Ethereum blockchain
* MetaMask for wallet interaction
* Sepolia testnet for test-network deployment
* Multiple test accounts for voting scenarios

### Example Test Flow

```text
Connect MetaMask
       ↓
Register Voter
       ↓
View Candidates
       ↓
Select Candidate
       ↓
Confirm Transaction
       ↓
Vote Recorded
       ↓
Verify Transaction
       ↓
View Results
```

---

## 🔐 Security Considerations

Blockchain provides strong data integrity and transparency, but a production-ready voting system requires additional security mechanisms.

Potential areas for improvement include:

* Strong voter identity verification
* Prevention of duplicate voting
* Secure smart-contract auditing
* Privacy-preserving voting
* Access control
* Protection against wallet compromise
* Secure backend configuration
* Comprehensive penetration testing

---

## 👨‍💻 My Contribution

**Dhruv Sharma**

As a contributor to this project, my work included:

* Blockchain and Web3 integration
* Voting system implementation
* Frontend integration
* Testing and debugging
* Smart-contract interaction
* Project documentation
* GitHub project management

> Contribution details are listed to accurately represent my involvement in the collaborative project.

---

## 🤝 Project Collaboration

This project was developed collaboratively with **Bhavya Goel**.

The original collaborative project is available here:

**Original Repository:**
https://github.com/bhavyweb3/Decentralized-Voting-System

This repository is maintained independently by **Dhruv Sharma** for academic, portfolio, and professional purposes, while giving proper credit to the original project collaboration.



## 🚀 Future Improvements

Possible future enhancements include:

* [ ] Advanced voter authentication
* [ ] Role-based access control
* [ ] Improved smart-contract security
* [ ] Real-time voting results
* [ ] Responsive mobile interface
* [ ] IPFS-based decentralized storage
* [ ] Zero-knowledge privacy mechanisms
* [ ] Better transaction monitoring
* [ ] Automated smart-contract testing
* [ ] Production-grade deployment

---

## 🎯 Learning Outcomes

Through this project, I gained practical experience in:

* Blockchain fundamentals
* Ethereum architecture
* Solidity smart contracts
* Web3 integration
* MetaMask wallet integration
* Blockchain transactions
* Decentralized application development
* Smart-contract testing
* Git and GitHub collaboration

---

## ⚠️ Disclaimer

This project is developed **for academic and educational purposes only**.

It is a prototype demonstrating blockchain-based voting concepts and should **not be used for real-world elections** without extensive security auditing, privacy protection, identity verification, legal compliance, and professional testing.

---

## 📜 License

This project is intended for educational and academic use.

Please review the repository history and project contributors before redistributing or using the project commercially.

---

## ⭐ Support

If you find this project useful for learning about Blockchain and Web3 development, consider giving the repository a ⭐ on GitHub.

---

### 👤 Author

**Dhruv Sharma**

B.Tech Computer Science Engineering — Blockchain

GitHub:
https://github.com/Dhruvchain

LinkedIn:
https://www.linkedin.com/in/dhruv-sharma-8b870431b/

---

**Built with ❤️ while learning Blockchain & Web3 Development.**
