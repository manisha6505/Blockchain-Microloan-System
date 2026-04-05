💸 Blockchain-Powered Microloan Payment Platform

A decentralized microloan application that allows borrowers and lenders to interact directly without traditional banks or middlemen.
This DApp uses Ethereum smart contracts to automate loan creation, funding, and repayment—offering security, transparency, and improved financial accessibility.

🚀 Key Features

👤 Borrower Panel — Submit loan requests, check previous loans, and monitor repayment progress.

💰 Lender Panel — View available loan requests, fund them safely, and track repayments.

🔐 Solidity Smart Contracts — Automatically manage loan approval, funding, and repayment logic.

💳 Credit Score Mechanism — Credit score adjusts based on borrower repayment performance.

🌐 MetaMask Support — Easily connect your Ethereum wallet for secure transactions.

📊 Transparent Ledger — All activities are permanently recorded on the blockchain.

🎨 Clean User Interface — Modern and responsive UI for a smooth Web3 experience.

🧩 How to Run the Project Locally

1️⃣ Clone the Repository
git clone https://github.com/manisha6505/Blockchain-Microloan-System.git
cd Blockchain-Microloan-System

2️⃣ Install Node Dependencies
npm install

3️⃣ Launch the Local Blockchain (Hardhat)
npx hardhat node

4️⃣ Deploy the Smart Contract
npx hardhat run scripts/deploy.js --network localhost

5️⃣ Start the Frontend

Open the index.html file in a browser (or use Live Server) and connect MetaMask to localhost:8545.

🛠️ Requirements

Make sure the following tools are installed before starting:

Node.js (v18 or higher) — Required for Hardhat and npm

npm — Package manager for JavaScript

Hardhat — Local Ethereum development environment

MetaMask Extension — For wallet connection and transactions

Ethers.js — To interact with the blockchain via JavaScript

VS Code — Recommended code editor

Chrome / Brave — Works best with MetaMask

Solidity Compiler — Comes with Hardhat for contract compilation

Optional tools for enhanced development:

✔ Hardhat Toolbox (testing & debugging)

✔ Live Server (quick frontend preview)

✔ Ganache (another local blockchain option)

🔒 Smart Contract Summary
struct Loan {
    uint id;
    address borrower;
    address lender;
    uint amount;
    uint interest;
    uint dueDate;
    bool isFunded;
    bool isRepaid;
    bool isDefaulted;
}

Main Functions:

requestLoan() — Allows borrowers to create a loan request.

fundLoan() — Lets lenders fund pending loan requests.

repayLoan() — Borrower makes loan repayments.

checkDefault() — Identifies overdue or unpaid loans.

getCreditScore() — Fetches the borrower’s credit score.

---

📸 Screenshots:

Home Page  
![Home Page](./image.png)

Borrower Dashboard  
![Borrower Dashboard 1](./image-4.png)  
![Borrower Dashboard 2](./image-5.png)  
![Borrower Dashboard 3](./image-6.png)

Lender Dashboard  
![Lender Dashboard 1](./image-3.png)  
![Lender Dashboard 2](./image-2.png)

Loan Cards (Borrower)  
![Loan Cards Borrower](./image-10.png)

Loan Cards (Lender)  
![Loan Cards Lender](./image-11.png)

Credit Score Display  
![Credit Score](./image-9.png)

Repay Loan  
![Repay Loan 1](./image-7.png)  
![Repay Loan 2](./image-8.png)

MetaMask Transaction Popup  
![MetaMask Transaction](./image-1.png)

---

👩‍💻 Developer

Manisha Choudhary 
📧 choudharymanisha0605@gmail.com

🪙 License

This project is licensed under the MIT License — you’re free to use, modify, and distribute it.
