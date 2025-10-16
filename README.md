_A BLOCKCHAIN-BASED LAND REGISTRY SYSTEM_

Since from time immemorial, the problems of land have persisted in Cameroon, Africa and the world at large. some of these problems have resulted in wars leading to the lost of lives. The issue has always been that people argue on who has what piece of land with people selling their land to more than one person and others selling land that doesn’t belong to them. Even when the land titles papers were brought the problem still persisted because people could still create fakes and then we are right back to where we started. I take an example of a case beside me where someone is building a fence on the road. It may not be known how the land was Partitioned when the people were selling but one thing is for sure they have sown into the road and there is no evidence to show that the fence is on the road or that part of the land was separated as a road so we are forced to accept it. This is how the existing land registry system looks like;

![Figure 1. Traditional land registry system](image.png)
*Figure 1. Traditional land registry system*


The issue with the existing land registry system is that In the existing land registry system, the land registrar cannot verify any existing dues on the land and
registrar will act assuming that all the land dues are clear . The registry office only makes a record of land
transactions, and it works based on the payment proof submitted by the seller and buyer but cannot verify its
validity independently and actual payment made. The corruption in the current system led to the rise of
the unidentified owners as well as it makes the record updating process tedious and costly due this reason poor
farmers cannot register the land title under their name, and consequently they become inaccessible to various
government schemes like loan on low rate, loan waivers and support for cultivation. The informal moneylenders
are trapping the poor farmers in the absence of any formal land title for money lending, and they pay the very
high cost on the lending amount and in the majority of cases are unable to repay the loan amount. The land
registry system depends upon the government departments for processing and the verification. As all the land
register database are not connected to the land registry system, it reduces the efficiency and equality of
the system. There are many issues related to Paper-based land registry system that has been summarized in this
section. As the land registry system is not digitalized, it is prone to the alteration. The process of land
registery is lenghthy and requires lots of paper verification, physical visits, check and bribery at every stage that
causes a lot of delay and wastage of time and money. Availability of record is another major issue as
the process of land registry involves a change of owners from time to time that takes time and it can not provide
real time details for any verification. Assessing these records require time, lots of visits and bribery and that
records also may not be synchronized. Land title issue is very conflict arising matter as most of the cases in
the court of land related issues are of land title dispute due to various reasons like double spending, fake records
and unable to rightly identify the genuine owners. Land double spending issue arises due to
the synchronization issue in the land registry system, and it is prone to tampering. The same person can sell
the same piece of land to multiple parties, and it can be traced at the later stage when the land mutation is being
done. Paper-based systems are very much prone to such issues.

this is where the blockchain land registry system comes in. Blockchain is an evolving technology with high security where information is stored in blocks and kept on different nodes. A blockchain consists of data sets which are composed of a chain of data packages (blocks) where a block comprises multiple transactions. The blockchain is extended by each additional block and hence represents a complete ledger of the transaction history. Blocks can be validated by the network using cryptographic means. In addition to the transactions, each block contains a timestamp, the hash value of the previous block (‘‘parent’’), and a nonce, which is a random number for verifying the hash. This concept ensures the integrity of the entire blockchain through to the first block (‘‘genesis block’’). Hash values are unique and fraud can be effectively prevented since changes of a block in the chain would immediately change
the respective hash value. If the majority of nodes in the network agree by a consensus mechanism on the validity of transactions in a block and on the validity of the block itself, the block can be added to the chain. This consensus mechanism ‘‘is the process in which a majority (or in some cases all) of network validators come to agreement on the state of a ledger. It is a set of rules and procedures that allows maintaining coherent set of facts between multiple participating nodes’’. Therefore, new transactions are not automatically added to the ledger. Rather, the consensus process ensures that these
transactions are stored in a block for a certain time (e.g., 10 min in the Bitcoin blockchain) before being transferred to the ledger. Afterwards, the information in the blockchain
can no longer be changed. In the case of Bitcoin, blocks are created by so-called miners who are rewarded with Bitcoins for validating the blocks. The example of Bitcoin illustrates that the principle of the blockchain cannot only change the process of money transactions. Using cryptography, people all over the world can trust each other and transfer different kinds of assets peer-to-peer over the internet. Here, people can upload their land documents and there is transparency as to who own what piece of land. It is also important to note that not every document is accepted as a land ownership document, it must have been approved by the government and the people involved in land transaction. and when a land is bought or sown there are details about it and if there are disputes, they can be resolved through the system.

This system will be a web platform that allows its users to create and manage accounts for which they are able to upload their land details, initiate land transactions, manage disputes and get notifications.

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

![Figure. 2 Block overview of the proposed solution](image-1.png)
*Figure. 2 Block overview of the proposed solution*

Government Authority: This enterprise is supplied with a unique deal with that can't be surpassed directly to every other district
resident or different member of Blockchain. This enterprise will begin with a application that manages the genesis block. In the
following step, site IDs are nevertheless dispensed among the addresses of the respective proprietors. Any sort of disputed land or
actual land misplaced because of unavoidable natural situations may be declared null and void by the address of government
officials. Therefore, such tokens will now no longer be eligible for any switch of possession. This is the legal deal with and has the
electricity to terminate the operation of the system by declaring that all tokens are invalid and do not work in the event of an
emergency or non-natural disassembly.
Land Owner: All assets IDs may be mapped to the address of the proprietor who has the ability to break up tokens into smaller
tokens and transfer possession of map tokens amongst different nodes in Blockchain with the permission of the brand-new
proprietor or new member of Blockchain. If tokens are mapped with owner's address called blank and blank, the tokens will now no
longer be able to parse or switch them, despite the fact that the unique owners' records will continue to be valid.
Non-members of Blockchain: Any citizen of the country, after confirmation of a proper national record-keeping system, may also be
a part of Blockchain without any other form of agreement to be met. The node can most effectively view information of residences
which can be on sale by present landowners. After obtaining possession of a specific a part of the token, the address is added to the
genesis block and referred to as the current token owner. The transaction is recorded on a blockchain similar to requests made by the
vendor and the buyer. The above businesses work simultaneously to maintain the integrity of the system. The luxury of moving land
possession with none sort of office work or criminal strategies eliminates the problem of investing money and time for trivial
reasons.

The system will be a distributed system. A distributed system is system where the independent computers collaborate over a network to achieve a common goal. Distributed systems are always determined by the ability of the system to do certain things. Some of these things are; the nodes must be separated but communicate through a network to achieve a goal, no global time or state, and the system must be transparent. Once a system is built as distributed, it will always be scalability, fault tolerance and allow for collaboration because of those characteristics. All these attributes of scalability, fault tolerance and collaboration can be seen in this system as explained below.


The scalability of this system is achieved through decentralized access and by reducing administrative bottlenecks. By eliminating manual processes, paperwork, and centralized verification, the system can handle a larger volume of verified transactions and simultaneous requests from many users more efficiently than traditional systems. 

Fault Tolerance is a core feature of this system due to distribution and redundancy. Since the complete land registry record is distributed and stored across multiple, independent nodes, the failure or compromise of any single node on the network does not affect the availability or integrity of the data. Every node (computer) in the network has a full copy of the entire ledger (all the blocks). If one node or a small number of nodes fail, the rest of the network continues operating and serving the data, ensuring high availability (24/7 access).

Collaboration is enforced through a shared, tamper-proof source of truth and consensus mechanisms. The blockchain acts as a single, verified source of land data that all stakeholders (government agencies, banks, notaries, buyers, and sellers) must agree upon (collaborate on) for a transaction to be added to the ledger. This increases trust since people do not have to assess the trustworthiness of the intermediary or other participants in the network. It is sufficient if people solely build trust in the system as a whole. The absence of intermediaries also fosters data security. The current practice of third parties collecting personal data implies the risk of security breaches. By utilizing the blockchain third parties can become obsolete, ultimately increasing user’s security.


*Technologies used*
This chapter discusses the various tools, technologies and standards used to build
the project. The tools are chosen considering their pros and cons, project scalability
concerns and sometimes adhering to governmental requirements. Some of the tools
are from new startups and under active development.

*Blockchain*
A blockchain is a decentralized database that is shared between network nodes and which is
a type of data storage system that stores information electronically. Blockchains are known
for their use in transactional systems in the industry, where it help to keep a secure and
decentralized record of transactions. The blockchain's originality guarantees better accuracy
and security of records, allowing to trust the system without requiring a trusted intermediary
party. 


*Ethereum Blockchain*
Ethereum is a decentralized blockchain network that is free to use. It allows anyone to create
and use blockchain-based decentralized applications. Ethereum is an open-source project
maintained by many people throughout the world, just like Bitcoin. No one controls or owns
Ethereum. It was created with the intention of being adjustable and versatile. On the
Ethereum platform, it is simple to construct new apps, and with the recent Homestead release,
those apps are now much safer to use.

*Solidity*
Solidity is a high-level object-oriented language derived from C++, Python, and JavaScript
for creating smart contracts. Smart contracts are computer programs that control how
accounts behave in the Ethereum chain. Solidity is a statically typed curly-braces
programming language that is used to develop smart contracts and is also aimed toward the
Ethereum Virtual Machine (EVM). It refers to currently executing contract instance
using keyword "this". Messages can be sent to other contract or the current contract by
the contract function, also with some gas fee and some amount of virtual money. An
implicit variable called "msg" holds details of the current message call. The information
includes caller address (i.e msg.sender), amount of money sent(i.e msg.value), etc.


*Smart Contract*
Smart contracts are simple programs that are used to automate and streamline the
implementation of an agreement so that all parties, without the need for any intermediaries
that run on a blockchain


*React JS*
ReactJS is a front-end JavaScript library for creating user interfaces using UI components
that are open-source. Meta and a community of individual developers and businesses
support it. With frameworks like Next.js, React may be used as a foundation for developing
single-page, mobile, or server-rendered applications. React, on the other hand, is solely
concerned with state management and rendering that information to the Document Object
Model (DOM), so constructing React apps frequently necessitates the usage of different
frameworks for routing and client-side functionality. 

![alt text](image-3.png)

