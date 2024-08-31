# Decentralized Document Verification System Using Blockchain and IPFS

This project introduces a secure and decentralized approach for document verification, leveraging the strengths of Blockchain and InterPlanetary File System (IPFS) technologies. By storing document hashes on the Blockchain and the documents themselves on IPFS, the system guarantees that documents remain immutable and can be reliably retrieved and authenticated by authorized users.

## Key Features

- Secure and Immutable Verification: Utilizes Blockchain and IPFS to create a tamper-proof environment for document verification.
- Decentralized Architecture: Eliminates single points of failure by distributing data and verification processes across a decentralized network.
- Efficient Verification Process: Enables quick and reliable document verification without the need for intermediaries.
- User-Friendly Interface: Provides an intuitive interface for uploading, storing, and verifying documents.
- Support for Diverse Document Types: Compatible with multiple formats and document types to cater to a wide range of verification needs.

## System Requirements

- Node.js and npm installed on your machine
- MetaMask Wallet for blockchain interactions
- IPFS API Credentials (API key and secret) available from Infura.io
  
## Installation

1. Clone this repository: 
   


2. Install the required packages:
  ``cd BlockChain-Based-Document-Verfication-With-IPFS``
  `` npm install``

## Deploy Smart Contract:
- Use Remix IDE to deploy contract.sol.
- Copy the deployed contract address and update the contractAddress field in app.js.
- Set the appropriate network URL and explorer URL from MetaMask settings.
   
## How to Use

1. Add Authorized Exporter:
- The system administrator must add exporters by entering their MetaMask address through the "Add Exporter" interface.
  
2. Upload a Document:
- Click "Upload Document" and select the desired file from your device. The document will be securely stored in IPFS, with its hash recorded on the Blockchain.

3. Verify a Document:
- Use the "Verify Document" option to select and verify a document. The system will retrieve and validate the document, ensuring it matches the stored hash on the Blockchain.

4. Authenticity Confirmation:
- The system will confirm whether the document is authentic, ensuring it has not been tampered with.

## Light Papaer -> https://drive.google.com/file/d/1I5iFOBDjCkuxDTvny-P_cEvLxaD7MdcQ/view?usp=share_link




