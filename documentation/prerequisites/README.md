## πππ¬π’π πππ«π¦π’π§π¨π₯π¨π π’ππ¬

### πΎπππ ππ πππππ ππ ππππππππ?
> - `Military exercise` carried out to test or improve tactical expertise are known as wargames
<div align=center>
<br>
<img src=https://user-images.githubusercontent.com/68887544/191426950-70fd286d-bbec-40cc-8c93-e93b83dc5e0a.png height=400px>
<br>
</div>
<br>

---

### π«πππππππππ πππππππ πͺππππππππππ πππ π΄πππππππ π¬πππππππ

- πͺππππππππππ
> - In a competition, organizers propose a challenge and invite people to participate. 
> - During the competition, the organizers determine the best participant according to some organizer-specified criteria. 
> - Participants often receive a score from which observers might infer that one participant is better than another, but not necessarily why. 
> - At the competitionβs end, the organizers crown a victor, perhaps also awarding a prize

- π΄πππππππ π¬πππππππ

> - Military exercises play a critical role in preparing forces to perform their assigned missions. 
> - Typically, a military unit will participate in exercises of increasing complexity as it prepares for deployment. 
> - Exercises also serve as intermediate evaluation opportunities for units after various training phases.
> - Additionally, exercise organizers often precisely dictate the prerequisite training. 
> - Most exercises try to immerse the unit in a realworld scenario similar to one the unit is expected to encounter while deployed. 
> - The military operates under the premise that if you train like you expect to fight, your fighting will mirror your training. 
> - So, the more realistic the training is, the greater likelihood of success in any real-world engagement.
> - Another fundamental feature of each exercise is the detailed feedback units receive regarding their performance. 
> - Deficiencies are noted, and units are expected to address them before future exercises or final deployment. 
> - The military supports entire organizations dedicated to crafting scenarios, hosting exercises, collecting performance data, and evaluating participating units.

- π²ππ π«πππππππππ

> - A key difference between competitions and exercises is that exercise organizers play a critical role, both before and after the exercise, in preparing participants and helping them address deficiencies.

Reference:
```
C. Eagle, βComputer Security Competitions: Expanding Educational Outcomes,β IEEE Security & Privacy, vol. 11, no. 4, pp. 69β71, Jul. 2013, doi: 10.1109/msp.2013.83.
```
---

### πΎππ 1.0, πΎππ 2.0 πππ πΎππ 3.0

- πΎππ 1.0
> - Web 1.0 refers to the earliest iteration of the World Wide Web. 
> - Web 1.0 included websites serving static content.
> - Web 1.0 can be considered a `read-only version of the web`, where the content of a website was served from a static file system rather than databases.

- πΎππ 2.0
> - Web 2.0 has been all about interactivity of users with the web.
> - Web 2.0 was more user-oriented, users started creating content themselves with the introduction of platforms like Facebook, Twitter and YouTube, and the internet space become more collaborative and social.
> - With Web 2.0, the web was no longer read-only, it become `read- and write-accessible` to users.

- πΊπππππππ πππ π·ππππππ πͺπππππππ ππ πΎππ 2.0
> - Data from the users is the key entity of this new web, leading to its exploitation. 
> - The `centralization` of web and user data by the internet giants is where users have made compromises to access these platforms.
> - As access to user data became a powerful asset for companies, data breaches began to occur. 
> - Applications built over Web 2.0 often experience data breaches and data leaks of user's data, which can sometimes include very sensitive data such as card credentials, passwords, etc.

- πΎππ 3.0
> - Web 3.0 is the next iteration of the web.
> - Web 3.0 could be considered a rethink of Web2.0 with `decentralization` as its foundation.

<br>

= | Web 2.0 Apps | Web 3.0 `DApps`
---|---|---
Computation | Server | `Peer-to-Peer Network`
Hosting | Web Server | Distributed CDNs (SWARM/IPFS)
Service Layer | HTTP API | `Smart Contracts`
Storage | Database | Distributed Storage, `Blockchain`

Reference:
```
A. K. Goel, R. Bakshi, and K. K. Agrawal, βWeb 3.0 and Decentralized Applications,β Materials Proceedings, vol. 10, no. 1, p. 8, 2022, doi: 10.3390/materproc2022010008.
```

---

### πΎπππ ππ ππππππππππ?

> - Blockchain is a distributed ledger which means all the parties taking part in the transaction or the parties present on the blockchain has the copy of the ledger and there is no centralised database. 
> - In case of any failure of the centralized database it may lead to data loss but with blockchain this problem is solved. 
> - Another important advantage provided is the transparency of the transactions.
> -  Hyperledger fabric, corda, and `ethereum` are the major platforms for blockchain development.

### πΎπππ ππ π¬πππππππ?

> - Ethereum is a project which is used to build the technology on which all transaction-based concepts can be built. 
> - It provides a system to end-developer for building software on formerly unexplored computer models in the mainstream. 
> - The key goal of this project is to facilitate transactions between individuals who would have no means to trust one another.
> - Ethereum is a transaction based state machine. 
> - It begins with a genesis state and incrementally execute a transaction to modify it into a final state. 
> - The state can contain various data as, balances, data pertaining, etc. 
> - There can be valid or invalid state changes. 
> - Invalid state changes can be due to invalid account balance modifications i.e. increase in receiverβs account balance without simultaneous reduction in the senderβs account balance.
> - Many transactions are combined in a block using Merkel tree and blocks are chained together using the cryptographic hash.
> - Blocks function as a journal, recording a series of transactions together with previous block and identifier for final state.

### πͺπππππππ ππ π¬πππππππ

> - Ethereum has an intrinsic currency called "Ether" or ETH, smallest sub-denomination of Ether is Wei.

### π¨ππππππ ππ π¬πππππππ

> - In Ethereum, state is made up of objects called as Accounts.
> - Each account has 20-bytes address. 
> - State-transition is transfer of value and information. Each account consist of four fields:
>   - 1) Nonce- Counter used to make sure that transaction is processed once
>   - 2) Ether balance
>   - 3) Contract Code
>   - 4) Storage
> - There are two types of accounts in ethereum:
>   - Externally Owned Accounts (EOAs), which are controlled by private keys.
>   -  Contract Accounts, which are controlled by their contract code and can only be activated by an EOA.

### πΎπππ ππ π?ππ π·ππππ?

> - Gas price is a scalar value equal to the number of Wei to be paid per unit of gas for all computation costs incurred as a result of the execution of the transaction.

### πΎπππ ππ π?ππ π³ππππ?

> - Every transaction has a specific amount of gas associated with it called as GasLimit. 
> - Gaslimit is the amount of gas which is implicitly purchased from the sender's account balance. 
> - We can refer gas limit as, the total amount of gas a sender is willing to purchase for the transaction to be executed.

###  π»ππππππππππ ππ π¬πππππππ

> - The term Transaction is used in Ethereum to refer to the signed data package that stores a message to be sent from an externally owned account.
> - Message call and account creation are the two types of transaction. 
> - Transactions contain the recipient of the message, a signature identifying the sender, the amount of ether and the data to send, as well as two values called Start (Gaslimit) and Gas price.

### π»ππππππππππ π·ππππππ

> - Check if the transaction is well-formed (i.e. has the right number of values), the signature is valid, and the transaction nonce matches the nonce in the sender's account. If not, return an error.
> - Calculate the transaction fee as START GAS * GASPRICE and determine the senderβs address from the signature. Subtract the fee from the sender's account balance and increment the sender's nonce. If there is not enough balance to spend, return an error.
> - Initialize GAS = START GAS, and take off a certain quantity of gas per byte to pay for the bytes in the transaction.
> - Transfer the transaction value from the sender's account to the receiverβs account. If the receiving account does not yet exist, create it. If the receiving account is a contract type account, run the contract code either to complete the transaction or until the execution runs out of gas.
> - If the value transfer fails due to the senderβs low balance or due to unavailability of gas, revert all state changes except the payment of the fees, and add the fees to the miner's account.
> -  Otherwise, refund the fees for all remaining gas to the sender, and send the fees for gas consumed by the miner.
<div align=center>
<br>
<img src=https://user-images.githubusercontent.com/68887544/191448928-c454ca10-5d01-4d95-a998-427b63123fc2.png>
<br>
</div>

### π»πππππππππππ ππππ ππ π¬πππππππ

Feature | Technologies
---|---
Data Storage | `Swarm is a distributed storage platform and content distribution service, a native base layer service of the ethereum web 3.0 stack.` The primary objective of Swarm is to provide a decentralized and redundant store for ethereum's public record, in particular, to store and distribute dapp code and data as well as blockchain data.
Web Technology |  Web 3.0 is an internet where core services like DNS and digital identity are decentralized. `Ethereum is perfectly suited to serve as shared back-end to a decentralized and secure internet`. Ethereum uses Web 3.0 as a platform for a decentralized application (DApp)
Client/Node Implementation | `Ethereum clients` are used for sending and receiving data. Wallet or custom applications connect to a client for transactions, may be for sending or receiving ethers, deploying a contract, executing a contract, initiating mining, etc. `Ethereum has many client/ node implementation as go-ethereum, parity, cpp-ethereum, pyethapp, etc.` Smart Contracts in ethereum are implemented using languages like Solidity, Lisp, etc.


### πͺππππππππ π¨πππππππππ ππ π¬πππππππ

> - A fundamental problem in distributed computing and multi-agent systems is to achieve overall system reliability in the presence of a number of faulty processes. 
> - This often requires processes to agree on some data value that is needed during computation. 
> - The algorithm involved in such processes is Consensus algorithm. 
> - There are mainly 3 types of consensus algorithms:
>   - Proof of Work (PoW)
>   - Proof of Stake (PoS)
>   - Proof of Authority (PoA)

- π·ππππ ππ πΎπππ (π·ππΎ)
> - Mining is the process of dedicating efforts to strengthen the series of transactions in one block over other competitor blocks.
> - Any node on public blockchain can act as a miner. 
> - The only requirement is that it should support resource requirement for mining in PoW.
> - In Proof of Work (PoW), miner has to solve the puzzle for validating the new block to be added. 
> - The first miner who gets the solution publishes it to the network. 
> - The difficulty level of puzzle changes for different blocks. 
> - Hence, the amount of computations differs for different blocks.
> - Hashing function takes input data and converts to Hash value also known as the message digest which is unique.
> - The hash value cannot be used for recreating the original data. 
> - Hence, the hashes used in such case are called as One Way Hashes
> - PoW uses GHOST protocol and ETHash algorithm. But, PoW is environmentally unfriendly due to its high power consumption

- π·ππππ ππ πΊππππ (π·ππΊ)
> - This algorithm is similar to PoW, the only difference is that here there is no competition as in PoW. 
> - Here, the network itself chooses the node which would validate the transaction known as the validator (not a miner). 
> - If node selected as validator does not validate the transaction then network selects next validator and process goes on untill the transaction is validated by any node. 
> - PoS uses CASPER protocol. 

- π·ππππ ππ π¨ππππππππ (π·ππ¨)
> - In this consensus algorithm, network allows for only those nodes which are authorized for validating the transaction.
> - The chain has to be signed off by the majority of authorities, in which case it becomes a part of the permanent record.
> -  This makes it easier to maintain a private chain and keep the block issuers accountable.

![image](https://user-images.githubusercontent.com/68887544/191476797-64e674c5-7e2c-4eb4-80f9-b4f97f714254.png)

Reference:
```
C. Saraf and S. Sabadra, βBlockchain platforms: A compendium,β 2018 IEEE International Conference on Innovative Research and Development (ICIRD), doi: 10.1109/ICIRD.2018.8376323
```

---

### πΎπππ ππ π πππππ ππππππππ?

> - A smart contract is a computer program having selfverifying, self-executing, tamper-resistant properties.
> - It takes transaction as a input, executes the corresponding code and triggers the output events.
> - All the transaction information are present in a smart contract and it executes automatically. 
> - The programming language Solidity is used to implement the smart contract in various blockchain platforms.

### πΎπππ πππ ππππ πππππππππππππππ ππ π πππππ ππππππππ?

> - Some characterizes of a smart contract are:
>   - Smart contract are machine readable code run on blockchain platform
>   - Smart contracts are part of one application program
>   - Smart contracts are event driven program
>   - Smart contracts are autonomous once created no need to monitor
>   - Smart contracts are distributed

### πΎπππ ππ ππππππππ?

> - Solidity is a high level language used to implement smart contracts.
> - Developing blockchian platform of solidity are Ethereum,ErisDB,Zeppelin and Counterparty.

Reference:
```
B. K. Mohanta, S. S. Panda, and D. Jena, βAn Overview of Smart Contract and Use Cases in Blockchain Technology,β 2018 9th International Conference on Computing, Communication and Networking Technologies (ICCCNT), Jul. 2018, doi: 10.1109/icccnt.2018.8494045.
```

---

### πΎπππ ππ π πππππππππππππ πππππππππππ?

> - A decentralized application is also referred to as a DApp.
> - DApps are open-source applications based on the Ethereum blockchain where a consensus is maintained between the user and programmer during the development process. 
> - The source code is available for examination and the application is stored in the blockchain to ensure trust and transparency.
> - The Ethereum blockchain is recognized as a biggest platform for decentralized applications.

Reference:
```
S. Sayeed, H. Marco-Gisbert, and T. Caira, βSmart Contract: Attacks and Protections,β IEEE Access, vol. 8, pp. 24416β24427, 2020, doi: 10.1109/ACCESS.2020.2970495.
```
