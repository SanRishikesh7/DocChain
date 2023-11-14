#DocChain
<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>

This project aims to create a secure and decentralized system for document storage and verification using Blockchain and InterPlanetary File System (IPFS) technologies. The system stores the hash of the documents in the Blockchain network and the documents themselves in the IPFS network. This ensures that the documents cannot be tampered with or altered, and they can be easily retrieved and verified by authorized parties.


## Requirements

- Node.js and npm installed on your system
- Ganache or any other Ethereum network client
- Wallet
- IPFS client (optional)

## Installation

1. Clone this repository
2. Install the required packages:
3. Open the in your browser using Liver Server Extension.
4. Connet Wallet.


## Usage

1. The owner of the system must first add an exporter to the list of authorized parties. This is done by clicking on the "Add Exporter" button and entering the exporter's Ethereum address.
2. Upload a document to the system by clicking on the "Upload Document" button and selecting a file from your computer. The document will be encrypted and stored in the IPFS network, and its hash will be recorded in the Blockchain.
3. Verify a document by clicking on the "Verify Document" button and entering its unique identifier (hash) in the input field. The system will retrieve the document from the IPFS network, decrypt it, and compare its hash with the one recorded in the Blockchain.
4. The system will display a message indicating whether the document is authentic or not.


## Acknowledgments

- Metamask documentation
- Solidity and Web3.js documentation
- IPFS documentation
- Truffle documentation




