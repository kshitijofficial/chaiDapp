# Chai Buying DApp

🍵 This is a beginner-friendly decentralized application (DApp) for purchasing chai using cryptocurrency while including a personalized message. ☕️

### Tutorial Video

[Chai Buying DApp Tutorial English](https://www.youtube.com/watch?v=YourVideoID)

[Chai Buying DApp Tutorial Hindi](https://youtu.be/NxDGHynpA4s?si=Up2pVEUws3KrYSRn)

Watch my tutorial video to learn how to use the Chai Buying DApp!

## Getting Started

To get this DApp running, follow the steps below:

### Clone the Repository

```
git clone <repository-url>
```

### Contract Compilation and Deployment

1. Install dependencies:
   ```
   npm install
   ```

2. Compile the contracts:
   ```
   npx hardhat compile
   ```

3. Create a `.env` file:
   - Mention the QuickNode Goerli/Sepoli URL and your private key in the `.env` file.

4. Deploy the smart contract:
   ```
   npx hardhat run scripts/finalDeploy.js --network <network-name>
   ```
   Replace `<network-name>` with the desired network (e.g., Goerli, Sepoli).

### Frontend Setup

1. Ensure you have MetaMask installed in your browser.

2. Navigate to the `client` directory:
   ```
   cd client
   ```

3. Install frontend dependencies:
   ```
   npm install
   ```

4. Start the frontend server:
   ```
   npm start
   ```

## Usage

Once the DApp is set up:

1. Connect your MetaMask wallet to the DApp.
2. Send cryptocurrency to purchase chai.
3. Write a sweet message to accompany your purchase.
4. Enjoy your chai!
