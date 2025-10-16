_A BLOCKCHAIN-BASED LAND REGISTRY SYSTEM_

Since from time immemorial, the problems of land have persisted in Cameroon, Africa and the world at large. some of these problems have resulted in wars leading to the lost of lives. The issue has always been that people argue on who has what piece of land with people selling their land to more than one person and others selling land that doesn’t belong to them. Even when the land titles papers were brought the problem still persisted because people could still create fakes and then we are right back to where we started. I take an example of a case beside me where someone is building a fence on the road. It may not be known how the land was Partitioned when the people were selling but one thing is for sure they have sown into the road and there is no evidence to show that the fence is on the road or that part of the land was separated as a road so we are forced to accept it.

People have been dragged into deals that they did not know that were fake and afterwards they see people farming on their lands others even go the next day to see building materials while others have gone to see houses and fences already being built on the land they claim to have purchased. The problem is that who will they address this injustice to. Most of the people that have these problems do not know how to resolve them. some even go as far as taking matters into their own hands which end up resulting in conflicts and wars and in the end, there is bloodshed for nothing. There are conflict resolutions methods that have been put in place by the government but the transparency and access to these methods are sometimes costly and some even end in injustice. 

this is where the blockchain land registry system comes in. Blockchain is an evolving technology with high security where information is stored in blocks and kept on different nodes. A blockchain consists of data sets which are composed of a chain of data packages (blocks) where a block comprises multiple transactions. The blockchain is extended by each additional block and hence represents a complete ledger of the transaction history. Blocks can be validated by the network using cryptographic means. In addition to the transactions, each block contains a timestamp, the hash value of the previous block (‘‘parent’’), and a nonce, which is a random number for verifying the hash. This concept ensures the integrity of the entire blockchain through to the first block (‘‘genesis block’’). Hash values are unique and fraud can be effectively prevented since changes of a block in the chain would immediately change
the respective hash value. If the majority of nodes in the network agree by a consensus mechanism on the validity of transactions in a block and on the validity of the block itself, the block can be added to the chain. According to Swanson (2015), this consensus mechanism ‘‘is the process in which a majority (or in some cases all) of network validators come to agreement on the state of a ledger. It is a set of rules and procedures that allows maintaining coherent set of facts between multiple participating nodes’’. Therefore, new transactions are not automatically added to the ledger. Rather, the consensus process ensures that these
transactions are stored in a block for a certain time (e.g., 10 min in the Bitcoin blockchain) before being transferred to the ledger. Afterwards, the information in the blockchain
can no longer be changed. In the case of Bitcoin, blocks are created by so-called miners who are rewarded with Bitcoins for validating the blocks. The example of Bitcoin illustrates that the principle of the blockchain cannot only change the process of money transactions. Using cryptography, people all over the world can trust each other and transfer different kinds of assets peer-to-peer over the internet. Here, people can upload their land documents and there is transparency as to who own what piece of land. It is also important to note that not every document is accepted as a land ownership document, it must have been approved by the government and the people involved in land transaction. and when a land is bought or sown there are details about it and if there are disputes, they can be resolved through the system.

This is a web platform that allows its users to create and manage accounts for which they are able to upload their land details, initiate land transactions, manage disputes and get notifications.

1. User Management

FR1.1: The system shall allow users to create and manage accounts the user could either be a landowners, buyers, validators or admin.

FR1.2: The system shall implement a Know Your Customer (KYC) process to verify the identity of users before allowing registration or transactions.

FR1.3: The system shall allow different roles:

Regular user (landowner/buyer)

Validator (government agent or community authority)

Admin (platform operator)

2. Land Registration

FR2.1: The system shall allow landowners to register land by submitting ownership details and land documents of the land.

FR2.2: The system shall validate the submission of the details and documents before creating a blockchain land token (NFT or unique ID).

FR2.3: The system shall store supporting documents on a decentralized file system (e.g., IPFS) and link it to the blockchain record.

FR2.4: The system shall notify validators to approve or reject a registration request.

FR2.5: Once approved, the system shall mint a tokenized land title to the owner’s wallet address.

3. Land Ownership Verification

FR3.1: The system shall allow any user to search land records using parameters like land ID, owner name or location.

FR3.2: The system shall retrieve the current ownership status directly from the blockchain.

FR3.3: The system shall display a land title summary, ownership history, and document hash.

4. Land Transactions (Smart Contracts)

FR4.1: The system shall allow users to initiate land transfers by entering the name or id of the buyer, seller, and payment details.

FR4.2: The system shall automatically execute land transfers via a smart contract once payment is confirmed.

FR4.3: The system shall update ownership records on the blockchain post-transaction.

FR4.4: The system shall log all transactions in a public transaction ledger something like a dashboard.

5. Dispute Management

FR5.1: The system shall allow users to file land ownership or transaction disputes.

FR5.2: The system shall assign disputes to a panel of community validators or legal authorities.

FR5.3: The system shall track the status of each dispute and allow all parties to upload supporting evidence.

FR5.4: The system shall log dispute outcomes immutably on the blockchain.

The system will be a distributed system. A distributed system is system where the independent computers collaborate over a network to achieve a common goal. Distributed systems are always determined by the ability of the system to do certain things. Some of these things are; the nodes must be separated but communicate through a network to achieve a goal, no global time or state, and the system must be transparent. Once a system is built as distributed, it will always be scalability, fault tolerance and allow for collaboration because of those characteristics. All these attributes of scalability, fault tolerance and collaboration can be seen in this system as explained below.

The scalability of this system is achieved through decentralized access and by reducing administrative bottlenecks. By eliminating manual processes, paperwork, and centralized verification, the system can handle a larger volume of verified transactions and simultaneous requests from many users more efficiently than traditional systems. 

Fault Tolerance is a core feature of this system due to distribution and redundancy. Since the complete land registry record is distributed and stored across multiple, independent nodes, the failure or compromise of any single node on the network does not affect the availability or integrity of the data. Every node (computer) in the network has a full copy of the entire ledger (all the blocks). If one node or a small number of nodes fail, the rest of the network continues operating and serving the data, ensuring high availability (24/7 access).

Collaboration is enforced through a shared, tamper-proof source of truth and consensus mechanisms. The blockchain acts as a single, verified source of land data that all stakeholders (government agencies, banks, notaries, buyers, and sellers) must agree upon (collaborate on) for a transaction to be added to the ledger. This increases trust since people do not have to assess the trustworthiness of the intermediary or other participants in the network. It is sufficient if people solely build trust in the system as a whole. The absence of intermediaries also fosters data security. The current practice of third parties collecting personal data implies the risk of security breaches. By utilizing the blockchain third parties can become obsolete, ultimately increasing user’s security.


