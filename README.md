# Centralized Grievance Portal

## Overview

The Centralized Grievance Portal is a blockchain-powered platform built on Algorand, designed to securely manage and track complaints with real-time updates. By leveraging Algorand’s fast and efficient blockchain, the system ensures transparency, immutability, and tamper-proof complaint records, providing a trustworthy and auditable grievance resolution process.

## Features
- **Decentralized Complaint Logging** – Users submit grievances, which are recorded immutably on the Algorand blockchain.
- **Real-Time Status Updates** – Track complaint progress (Pending, In Review, Resolved) with instant blockchain updates.
- **Smart Contracts for Resolution Workflow** – Automated rules for complaint escalation and resolution.
- **Tamper-Proof Records** – All grievances and responses are stored securely using Algorand Smart Contracts (ASC1).
- **User & Admin Roles** – Role-based access for users, administrators, and auditors.
- **Audit Trail** – Full transparency with a verifiable history of complaint resolutions.
- **Fast & Low-Cost Transactions** – Powered by Algorand’s high-speed, low-fee blockchain.
- **Integration with Algorand Wallets** – Secure user authentication and complaint submission.

## Tech Stack
- ***Blockchain***: Algorand
- ***Smart Contracts***: PyTeal (Python-based smart contracts for Algorand)
- ***Frontend***: React.js / Next.js
- ***Backend***: Node.js / FastAPI
- ***Database***: PostgreSQL / IPFS (for metadata & document storage)
- ***Authentication***: Algorand Wallets (Pera Wallet, MyAlgo)
- ***Payments***: ALGO for priority grievance handling
- ***Hosting***: AWS / Vercel / Fleek

## Smart Contract Workflow

 1️. User submits complaint → Recorded on blockchain
 
 2️. Admin reviews and updates status → Smart contract logs updates
 
 3️. Complaint resolution recorded → Immutable final status stored
 
 4️. Audit trail accessible → Ensuring transparency

## API Endpoints

#### Authentication & User Management

    POST /register – Register a new user
    POST /login – User authentication

#### Complaint Management

    POST /complaint – Submit a new grievance
    GET /complaint/:id – Retrieve the status of a complaint
    PUT /complaint/:id – Update complaint status (Admin only)

#### Admin Functions

    GET /complaints – View all complaints (Admin only)
    DELETE /complaint/:id – Remove a complaint (Admin only)

## Contributing

1. Fork the repository

2. Create a feature branch

3. Commit changes

4. Submit a pull request

## License

License This project is licensed under the MIT License.
