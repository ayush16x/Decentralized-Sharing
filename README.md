# Decentralized Image Upload and Sharing

A decentralized application that allows users to upload images to IPFS and manage access control via a Solidity smart contract. The system ensures secure, immutable storage and enables permission-based image sharing.

Features

Decentralized Storage: Uploads images to IPFS for distributed and tamper-proof storage.

Smart Contract Access Control: Solidity-based contract manages ownership and permissions.

User Permissions: Grant or revoke access to specific users directly through the smart contract.

React Frontend: Clean interface for uploading images and accessing shared images.

Tech Stack

Solidity - Smart contract for access management

Hardhat - Smart contract development environment

React.js - Frontend interface

IPFS / Pinata - Decentralized file storage

Setup
1. Clone the repository
git clone https://github.com/your-username/decentralized-image-upload.git

2. Install Hardhat dependencies
cd Dgdrive3.0
npm install

3. Compile the smart contract
npx hardhat compile

4. Deploy the contract
npx hardhat run scripts/deploy.js --network <network-name>

5. Install React client dependencies
cd client
npm install

6. Start the React app
npm start

Configuration
Environment Setup

Get Pinata API keys.

Add them to the required React file (e.g., FileUpload.js).

Update Contract Address

After deployment, update the contract address in App.js.

How to Use

Connect Wallet

Use MetaMask to interact with the contract.

Upload Image

Upload an image to store on IPFS via Pinata.

Manage Access

Grant/revoke access to other users using their wallet address.

View Images

Use the "Get Data" feature to view images you own or have been granted access to.
