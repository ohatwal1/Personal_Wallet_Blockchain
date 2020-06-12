# Personal_Wallet_Blockchain

This is a small introductory project created to get an idea about blockchain technology.


# Blockchain :

- A Blockchain is a type of diary or spreadsheet containing information about transactions. Each transaction generates a hash. A hash is a string of numbers and letters. Transactions are entered in the order in which they occurred. The order is very important. 
- The hash depends not only on the transaction but on the previous transaction's hash. Even a small change in a transaction creates a completely new hash. The nodes check to make sure a transaction has not been changed by inspecting the hash. Each block refers to the previous block and together make the Blockchain. 
- The Blockchain updates itself every 10 minutes.

# Wallet :

- A wallet is a string of numbers and letters, such as 18c177926650e5550973303c300e136f22. This is an address that will appear in various blocks within the Blockchain as transactions take place. 
- No visible records of who did what transaction with who, only the number of a wallet. The address of each particular wallet is also a Public key.

# Requirements

-	Truffle Framework: npm install -g truffle@4.1.13
-	Ganache: Download and install the GUI Client



Truffle is the framework used to easily manage and deploy our Solidity codes. 
Ganache runs a local instance of the Ethereum network for our testing purposes.



Steps are explained in detail in Procedure.doc 
