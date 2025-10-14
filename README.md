_A BLOCKCHAIN-BASED LAND REGISTRY SYSTEM_

This is a web platform that allows its users to create and manage accounts for which they are able to apload their land details, initaite land transactions, manage despute and get notifications.

1. User Management

FR1.1: The system shall allow users to create and manage accounts (landowners, buyers, validators, admin).

FR1.2: The system shall implement a Know Your Customer (KYC) process to verify user identity before allowing registration or transactions.

FR1.3: The system shall allow different roles:

Regular user (landowner/buyer)

Validator (government agent or community authority)

Admin (platform operator)

2. Land Registration

FR2.1: The system shall allow landowners to register land by submitting ownership details and land documents.

FR2.2: The system shall validate the submission before creating a blockchain land token (NFT or unique ID).

FR2.3: The system shall store supporting documents on a decentralized file system (e.g., IPFS) and link it to the blockchain record.

FR2.4: The system shall notify validators to approve or reject a registration request.

FR2.5: Once approved, the system shall mint a tokenized land title to the owner’s wallet address.

3. Land Ownership Verification

FR3.1: The system shall allow any user to search land records using parameters like land ID, owner name, location, etc.

FR3.2: The system shall retrieve the current ownership status directly from the blockchain.

FR3.3: The system shall display a land title summary, ownership history, and document hash.

4. Land Transactions (Smart Contracts)

FR4.1: The system shall allow users to initiate land transfers by entering buyer, seller, and payment details.

FR4.2: The system shall automatically execute land transfers via a smart contract once payment is confirmed.

FR4.3: The system shall update ownership records on the blockchain post-transaction.

FR4.4: The system shall log all transactions in a public transaction ledger.

5. Dispute Management

FR5.1: The system shall allow users to file land ownership or transaction disputes.

FR5.2: The system shall assign disputes to a panel of community validators or legal authorities.

FR5.3: The system shall track the status of each dispute and allow all parties to upload supporting evidence.

FR5.4: The system shall log dispute outcomes immutably on the blockchain.

The scalability of this system is achieved through decentralized access and reduced administrative bottlenecks. By eliminating manual processes, paperwork, and centralized verification, the system can handle a larger volume of verified transactions and simultaneous requests from many users more efficiently than traditional systems.


Fault Tolerance is a core feature due to distribution and redundancy. Since the complete land registry record is distributed and stored across multiple, independent nodes, the failure or compromise of any single node does not affect the availability or integrity of the data. Every node (computer) in the network has a full copy of the entire ledger (all the blocks). If one node or a small number of nodes fail, the rest of the network continues operating and serving the data, ensuring high availability (24/7 access).

Collaboration is enforced through a shared, tamper-proof source of truth and consensus mechanisms. The blockchain acts as a single, verified source of land data that all stakeholders (government agencies, banks, notaries, buyers, and sellers) must agree upon (collaborate on) for a transaction to be added to the ledger. This removes the reliance on bilateral trust and makes information sharing seamless and immediate.
