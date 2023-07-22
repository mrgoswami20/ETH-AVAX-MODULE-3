# ETH-AVAX-MODULE-3

This is a simple smart contract to create your own token on a local HardHat network. The contract owner should be able to mint tokens to a provided address. Any user should be able to burn and transfer tokens.

## Connecting Local Hardhat Network with Remix
Follow the steps below to connect your local Hardhat network with Remix and interact with a contract.

Step 1: Navigate to Project Directory
Open your terminal and navigate to the project directory where your Solidity contract is located.

Step 2: Run `npm install @remix-project/remixd` Command
In the terminal, run the following command to start the `remixd` service:
```
npx remixd -s <project_directory>--remix-ide https://remix.ethereum.org
```
Replace `<project_directory>` with the absolute path to your project directory. This will create a connection between Remix IDE and your local project directory.

Step 3: Open Remix IDE
Open your web browser and go to [Remix IDE](https://remix.ethereum.org).

Step 4: Connect with Localhost Workspaces
In Remix IDE, Switch "default_workspace" to "Localhost" button in the top-right "Workspaces" corner. This will connect your project directory on remix IDE.

Step 5: Compile the contract
In the Remix IDE, find and open your ".sol" file in your contract folder and switch to the "Solidity Compiler" tab in the left panel. Click on the "Compile" button to compile the contract. Make sure the compiler version matches the pragma statement in your contract.

Example Contract:
```solidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

contract MyToken {
    // Contract code here...
}
```
Step 6: Deploy and Interact with the Contract
Switch to the "Deploy & Run Transactions" tab in the Remix IDE. From the "Environment" dropdown, select "Injected Web3" to connect to your local Hardhat network.

Click on the contract name under the "Deployed Contracts" section. You will see the contract's functions and variables. You can deploy the contract by clicking the "Deploy" button.

Once the contract is deployed, you can interact with its functions by entering the required parameters and clicking the respective function buttons.

Congratulations! You have successfully connected your local Hardhat network with Remix and deployed/interacted with a contract.

Note: Make sure your local Hardhat network is running (`npx hardhat node`) and that you have the necessary dependencies installed (`npm install`).

Please refer to the provided code and adjust it to meet your specific contract requirements. Add relevant information and code in a structured manner within the `Token` contract.

## Authors

Rohit kumar goswami


## License

This project is licensed under the MIT License
