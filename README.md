 🧪 Testing Smart Contract

A Solidity smart contract for testing basic functionalities like setting and updating a message. This contract includes an event to log message updates.

 🚀 Features
 Set Initial Message – Set a custom initial message during contract deployment.
 Update Message – Allows updating the stored message.
 Event Logging – Logs old and new messages when updated.



 🛠️ Tech Stack
 Solidity (v0.8.26) – Smart contract logic.
 Ethereum – Blockchain network for deployment.
 MetaMask – For interacting with the contract.



 📜 Smart Contract Explanation

 📌 Files
1. Testing.sol – Main contract for testing string storage and update.
   


 📌 Functions
 🔹 Testing.sol
 constructor(string memory _message) – Initializes the contract with a custom message.
 updateMessage(string memory _newMessage) – Updates the stored message with a new value.
 MessageUpdated (event) – Logs the old and new messages when updated.



 📦 Deployment & Usage
 1️⃣ Deploy the Smart Contract
1. Deploy Testing.sol contract by providing an initial message as a constructor parameter.

 2️⃣ Interact with the Contract
 Set Initial Message – On deployment, set the initial message.
 Update Message – Call updateMessage(newMessage) to update the stored message.



 ❗ Important Notes
 The contract includes an event to log changes, which can be captured by external tools like web3.js or ethers.js.



 📜 License
This project is opensource under the MIT License.

🚀 Developed by [0xSmartCoder](https://github.com/0xSmartCoder)
