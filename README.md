# 🗳️ BallotChain

A **decentralised voting system** built on **Ethereum blockchain technology**, designed to ensure **transparency, security, and immutability** in the election process.  

Originally developed as a **final-year IT degree project**, now being extended into a more robust and feature-rich platform.  

---

## 🚀 Features

- **Blockchain-based elections** — secure, transparent, and tamper-proof.  
- **Admin-controlled election setup** — create and manage elections with candidate details.  
- **Voter registration & verification** — users register with their blockchain account; admin verifies eligibility.  
- **Decentralised voting process** — eligible voters cast votes anonymously through the blockchain.  
- **Real-time result declaration** — results become available immediately once the election is ended.  
- **Scalable workflow** — supports elections of varying sizes.  

---

## 🔄 System Workflow

1. **Admin launches election**  
   - Deploys the system on the Ethereum Virtual Machine (EVM).  
   - Creates an election instance with candidate details.  

2. **Voter registration**  
   - Users connect to the blockchain network and register.  
   - Registration details (address, name, phone) appear on the admin panel.  

3. **Verification by admin**  
   - Admin validates voter information.  
   - Approved users become eligible to vote.  

4. **Voting**  
   - Verified users cast their votes securely.  

5. **Closing election & result announcement**  
   - Admin ends the election.  
   - Results are displayed, with the winner highlighted.  

---

## 🛠️ Tech Stack

- **Smart Contracts** → Solidity  
- **Blockchain Development** → Truffle, Ganache CLI  
- **Frontend** → React.js (client app)  
- **Ethereum Wallet** → MetaMask  
- **Backend** → Node.js  

---

## ⚙️ Development Setup

### ✅ Requirements
- [Node.js](https://nodejs.org/)  
- [Truffle](https://trufflesuite.com/)  
- [Ganache CLI](https://trufflesuite.com/ganache/)  
- [MetaMask](https://metamask.io/) (browser extension)  

### 📥 Installation

```bash
# Clone the repository
git clone https://github.com/your-username/BallotChain.git
cd BallotChain

# Install dependencies
npm install -g truffle ganache-cli
