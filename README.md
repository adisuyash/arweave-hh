# Full stack development with Arweave, Warp, and Next.js

This project is a locally-running full-stack application built on Arweave, inspired by Nader Dabit's tutorial: "How to build a full stack application on Arweave with smart contracts running on Smartweave via Warp Protocol" [Nader Dabit's Tutorial on Building a Full-Stack App on Arweave](https://www.youtube.com/watch?v=cGLMN5A2C4E).

Key Points:

Technology Stack:
Arweave
Smartweave
Warp Protocol (potentially Next.js based on Dabit's tutorial)
Development Stage: Local development (not deployed)
Purpose:
This project serves as a starting point for building permanent applications on Arweave using the guidance provided by Nader Dabit's tutorial.
Due to limited resources on Arweave development, this project leverages Dabit's tutorial as a foundation.

## Getting started

### Prerequisites

To run this app, you should have:

- Node.js installed on your machine
- [ArConnect](https://www.arconnect.io/) wallet extension
  
### Deploying and testing 

- Retreive Arweave tokens (available from the faucet [here](https://faucet.arweave.net/) or from an exchange)
- Install [ArConnect wallet](https://www.arconnect.io/)
- Download and save wallet in a file named `wallet.json`

## Running this project

To run the app, follow these steps:

1. Clone the project

```sh
git clone https://github.com/adisuyash/arweave-hh.git
```

2. Change into the directory and install the dependencies

```sh
cd arweave-hh

npm install

# or

yarn
```

3. Deploy the contract to testnet

From the `warp` directory, run the following command:

```
node deploy
```

4. Run the Next.js app

From the root directory, run the following command:

```sh
npm run dev
```