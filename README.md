# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a script that deploys that contract.

Try running some of the following tasks:

To start the project 

-> install required NPM Files on Decentralized Folder, Client and Server ```using npm i```

On Decentralized Folder run the following commands
 ```shell
npx hardhat node
npx hardhat run --network localhost scripts/deploy.js
```
On Server Folder run the following command
```shell
node index.js
```
On CLient Folder Run the following Command
```shell
npm start
```
Pinata Setup (IPFS Integration)
To enable decentralized file storage using IPFS via Pinata, follow these steps:

1. Create a Pinata Account
 Go to https://www.pinata.cloud and sign up.
Verify your email to activate the account.

2. Generate API Keys
 After logging in, navigate to the API Keys section in your dashboard.
 Click "New Key", give it a name, and choose the required permissions (Admin for full access).
 Copy the API Key and Secret API Key and store them securely. You’ll need them in your environment variables.

3. Install Pinata SDK
Install the Pinata SDK in your Node.js project:
```shell
npm install @pinata/sdk
```

4. Configure Environment Variables
   PINATA_API_KEY=your_api_key_here
   PINATA_SECRET_API_KEY=your_secret_key_here


**✋❗️❕ Crypto Wallet is strictly necessary ❕❗️✋**

