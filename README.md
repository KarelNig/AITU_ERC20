Overview
The AITU_Token is an ERC-20 token designed to represent university-related assets on the Ethereum blockchain. It inherits from the OpenZeppelin ERC-20 implementation and introduces custom functionality, including the tracking of transaction timestamps and receiver addresses.

Features
ERC-20 Standard Compliance
Transaction Timestamp Tracking
Sender and Receiver Address Retrieval
Usage
To use AITU_Token, you can deploy it on the Ethereum blockchain. Make sure you have the necessary tools, such as Remix or Truffle, and an Ethereum wallet like Metamask.
Functions

![image](https://github.com/KarelNig/AITU_ERC20/assets/123258977/9e65fabb-0650-40cc-9993-fc09aafddf69)
getLastTransactionTimestamp
Description: Returns the timestamp of the latest transaction block in a human-readable format.
Usage: Call this function to get the timestamp of the most recent transaction.

![image](https://github.com/KarelNig/AITU_ERC20/assets/123258977/73b3756f-034c-4193-b05a-2986853d8f61)
getTransactionSender
Description: Retrieves the address of the transaction sender.
Usage: Use this function to obtain the Ethereum address of the sender in the latest transaction.

![image](https://github.com/KarelNig/AITU_ERC20/assets/123258977/dbd5c933-d07c-46c1-b2e0-ed05208cd011)
getTransactionReceiver
Description: Retrieves the address of the transaction receiver.
Usage: This function returns the Ethereum address of the receiver in the second-to-last transaction.
