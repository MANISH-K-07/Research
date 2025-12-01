## 📄 Charity With Clarity: Crowdfunding Using Smart Contracts

IEEE ICRISST 2024 — Blockchain • Ethereum • Smart Contracts • Crowdfunding

---
🚀 Abstract

Traditional crowdfunding suffers from issues of trust, lack of transparency, and full control by intermediaries. This paper proposes an Ethereum-based smart-contract system in which donors can contribute funds securely, track every transaction, and vote on fund utilization requests made by organizations.
The smart contract enforces all rules automatically — ensuring decentralization, transparency, and fraud prevention — without relying on any centralized authority.

📄 Full paper is available in this repository under [IEEEXplore-Research-Paper.pdf](https://github.com/MANISH-K-07/Research/blob/main/IEEEXplore-Research-Paper.pdf).

---
🧠 Key Highlights

- ✔ Blockchain-powered donation transparency

- ✔ Ethereum smart contracts written in Solidity

- ✔ Role-based functionality for manager, contributors, and organizations

- ✔ Voting mechanism for request approvals

- ✔ Prevention of:

  - duplicate payments

  - illegal voting

  - unauthorized requests

- ✔ Fully tested on Remix IDE, Hardhat, MetaMask, and Sandbox blockchain
---
🏗️ Tech Stack

- Smart Contract : Solidity, Web3.js, Ethereum, Hardhat, Truffle
- Frontend	: React.js
- Deployment / Testing	: Remix IDE, MetaMask, Local Sandbox Blockchain
---
🔍 System Overview
1️⃣ sendEth()

Allows contributors to donate Ether to the campaign.

2️⃣ createRequest() (Manager Only)

Creates a fund withdrawal request from an organization.

3️⃣ voteRequest()

Contributors vote to approve or reject a request.

4️⃣ makePayment() (Manager Only)

Executes the payment only if majority approval is achieved.
Each transaction is immutably stored on the blockchain, enabling full traceability and eliminating manipulation.

---
🧪 Testing & Results

The paper includes detailed test scenarios such as:

- ✔ Successful transactions with majority votes

- ✔ Rejected requests when voter count < contributor majority

- ✔ Validation against:

  - unauthorized access

  - minimum contribution failure

  - duplicate votes

  - duplicate payments

Screenshots of both successful and failed transactions are included in the paper.

---
🏁 Conclusion

This research demonstrates how blockchain and Ethereum smart contracts can fundamentally transform crowdfunding by eliminating intermediaries, ensuring transparent fund management, and enabling contributor-driven decision-making. The system enforces trust through code, not third parties—resulting in a platform that is secure, decentralized, and tamper-proof.
With the growing adoption of Web3 technologies, smart-contract–based crowdfunding solutions hold strong potential for scalable, fraud-resistant, and globally accessible fundraising models.

---
