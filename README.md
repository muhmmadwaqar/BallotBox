# E-Voting App

A fully decentralized, secure, and transparent E-voting application built on the **Ethereum Blockchain** using **Solidity** for smart contracts and the **MERN stack** (MongoDB, Express.js, React.js, Node.js) for the frontend and backend. This application ensures a tamper-proof voting system, leveraging blockchain technology for trusted elections.

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSMaBZJ-VFnDKbUbDKJfIIFhgYhBvVH1_eDtA&usqp=CAU" height="200px" width="280px"/>

## Why Ethereum?
**Ethereum** is a decentralized, open-source blockchain platform that supports smart contracts—self-executing contracts with the terms directly written in code. By leveraging Ethereum, this app ensures every vote is securely recorded, immutable, and verifiable, providing a transparent and trustworthy voting system for all participants.

## About the DApp

The **E-Voting App** is designed with two key users:

1. **Admin**:
   - Can create new elections and register candidates directly on the blockchain.
   - Manages the election lifecycle, ensuring candidates are verified and listed securely.

2. **Voter**:
   - Selects an election from the available options and votes for their chosen candidate.
   - Can only cast one vote, ensuring fairness and security in the election process.

The decentralized nature of this app guarantees transparency and prevents vote manipulation or tampering, thanks to the immutability of blockchain technology.

## Key Dependencies
The app relies on the following technologies:

- **Node.js**: Backend runtime environment.
- **npm**: Package manager for JavaScript.
- **React.js**: Frontend framework for building user interfaces.
- **Web3.js**: Ethereum JavaScript API to interact with the blockchain.
- **Ganache-cli**: Personal blockchain for Ethereum development.
- **Truffle**: Development framework for Ethereum.
- **Solidity**: Programming language for writing smart contracts.
- **MongoDB**: Database for storing user and election data.
- **Metamask**: Browser extension for interacting with Ethereum networks.

## Getting Started

### Smart Contract Deployment

Follow these steps to deploy the smart contract on the blockchain:

1. Install **Ganache** and set up a workspace.
2. Install Truffle globally by running:
   ```bash
   npm install -g truffle
   ```
3. Compile and deploy the smart contracts with:
   ```bash
   truffle migrate --reset
   ```
4. Add the **Metamask** browser extension to manage Ethereum accounts and connect with the decentralized app (DApp).

### Running the React Development Server

Start the React application to interact with the blockchain:

```bash
cd blockchain
npm start
```

### Running the Node Server

Start the Node.js server for the backend:

```bash
cd server
npm run dev
```

## Architecture

This DApp uses a **client-server-blockchain** architecture:
- **Frontend**: Built with React.js to provide an interactive UI.
- **Backend**: Node.js and MongoDB handle authentication and data persistence.
- **Blockchain**: Ethereum smart contracts handle the election logic and voting records, ensuring decentralization.

## License

&copy; 2024 Muhammad Waqar. This project is licensed under the MIT License.
