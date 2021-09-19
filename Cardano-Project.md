# Fintech Case Study
## Overview and Origin
---
### Who is Cardano?
The Cardano Project consists of three entities
- Emurgo, founded by Ken Kodama - 43 Employees
- Input Output Hong Kong (IOHK), founded by Charles Hoskinson and Jeremy Wood- 301 Employees
- Cardano Foundation, founded by Charles Hoskinson and Michael Parsons- 75 Employees
---
### How did the project begin?
Cardano was incorporated in 2015, Switzerland. In late 2017 the company was funded by an ICO which produced $62.2mm.

Bitcoin is a first generation blockchain that provides the apex property rights. The vision of an internet of blockchains had the most momentum beginning with Ethereum, the largest second-generation blockchain. In 2015, the Cardano project came about to build a third generation blockchain to act as Financial Operating System and create a global set of systems that worked for all people no matter their wealth.

<br/>

### The big questions guiding the project

1. "How do we build a Universal Protocol that does everything the Legacy system does better and faster?"
2. "How do you build the minimum viable set of tools and social processes that once we push the domino, the system will grow to fill that need"


    >Cardano is a groundbreaking proof-of-stake blockchain network, being developed into a decentralized application (DApp) development platform with a multi-asset ledger and verifiable smart contracts. Built with the rigor of high-assurance formal development methods and based on peer-reviewed academic research, Cardano has an ethos of openness and transparency. All of the research and technical specifications that underpin Cardano are publicly published, and all Cardano development activity is made available to the public. Cardano is designed by a global team of experts who are leaders in disciplines ranging from distributed systems to programming languages and game theory and is jointly developed by IOHK and partners. IOHK develops the technology, the Cardano Foundation is responsible for supervising development and promoting Cardano, while Emurgo drives commercial adoption."
---

## Business Activities

---

### Cardano's core financial problems and the art of iteration

"Cryptocurrencies are protocols implemented as software. Protocols are simply intelligent conversations between participants. Software is ultimately the manipulation of data given some goal. Good software needs accountability, clear business requirements, repeatable processes, thorough testing and tireless iteration."

    1. Scalability
    2. Interoperability 
    3. Sustainability


### Scalability
Whereas the proof of work model forces every node to have the entire copy of the ledge, the election of a quorum for an epoch means we have a trusted set of nodes to maintain the ledger for a specific time period. It is trivial to elect multiple quorums concurrently and partition transactions to different quorums. 
"
- Transactions/second
- Network Bandwidth
- Data Scale

<br/>

### Interoperability
Consider how you transfer BTC to ETH to ADA? You go to an exchange - a centralized exchange such as coinbase. Why is this? Cryptocurennices aren't linked to each other. Cardano  intends to use sidechains to verify the ETH blockchain and BTC blockchain. Proof of Burn for cross-chain asset transfers.

Cardano will create interoperability with their project *Adrestia*.

> "Adrestia is a collection of products which makes it easier to integrate with Cardano. It comes in different flavours: SDK or high-level APIs. Depending on the use-cases you have and the control that you seek, you may use any of the components below."

Currently, Cardano's Adrestia can

- Help integrate other chains to the Cardano node 
- Enable multi-currency, script interaction and voting
- Provide libraries in additional coding languages


Interoperability has been solved with the Overledger technology which I will explain later.

<br/>

### Sustainability
How do we pay for things?

Proof of Stake - Stakeholders mine the tokens and get paid in ADA and a small portion goes to the decentralized 'Treasury' account. 

The treasury will provide Ada for *Project Catalyst*
1. Developers submit ballots, sorted by quality
2. Funds proposals are voted on by token holders


Where should we go?

 - Soft Forks 
 : a change to the software protocol where only previously valid transaction blocks are made invalid. Because old nodes will recognize the new blocks as valid, a soft fork is backwards-compatible. This kind of fork requires only a majority of the miners upgrading to enforce the new rules, as opposed to a hard fork that requires all nodes to upgrade and agree on the new version.




![Soft Fork](https://user-images.githubusercontent.com/90283529/133914587-e84d34c3-f80f-4171-b27e-316d4866591c.png)


 
 - Hard Forks 
 :is a radical change to a network's protocol that makes previously invalid blocks and transactions valid, or vice-versa. A hard fork requires all nodes or users to upgrade to the latest version of the protocol software.


![Hard Fork](https://user-images.githubusercontent.com/90283529/133914582-522f3c58-fef8-4d35-aa37-ccad96f8a514.png)


<br/>


### What competitive advantage does Cardano have?

Cardano has the ability to go from a good company to a great company through Charles Hoskinson's leadership. Jim Collins studied what makes a company go from good to great and he outlines disciplined people, thought, and action as characteristics of a good company. Cardano is already a 'good company' as Academia requires discipline, is repeatable, and is a lasting institution so the question becomes what does it take to become 'great'. Collins provides two concepts - 'Level five leader' and 'Flywheel'

Level five leader characteristics
 - Laser focused on the vision, the market, and the problems
 - Builds successors
 - Normal people. Charles runs a farming operation at his home Colorado to keep close to hard physical labor, to the earth

The flywheel model sugguests -

    If you do A, you almost can’t help but do B

    If you do B, you almost can’t help but do C

    If you do C, you almost can’t help but do A


Cardano's flywheel - 

    If new protocols are created, you almost can't help but see innovation

    If innovations are made, you will see individuals, governments and the private sector use the system

    If you get more users, the treasury funds new projects creating additional/updated protocols


---

## Current technologies

---

**Ouroboros** 
: Ouroboros breaks the physical world into Epochs which are made up of slots lasting one second each. Slot leaders validate transactions, create transaction blocks, and add new blocks to the Cardano blockchain. Being the slot leader is similar to the person who discovers the block in bitcoin with less cost. Slot leaders can construct and maintain additional blocks and additional chains allowing for sidechains and potentially parrallel chains. 

**Plutus Platform**
: Cardano's Smart Contracts platform. Haskell, a functional programming language, is used to create Plutus.

**Atla Prism**
: Dentralized Identity platform including a mobile app, browser wallet, and a smart card. People own their credentials which can be verifiable from anywhere. The end of data breaches and identity theft. The use cases include everything you need an identification for.

**Marlowe Playground**
: "Marlowe is special-purpose language for financial contracts on Cardano, allowing contracts to be written in the language of finance, rather than using a general-purpose language on the blockchain."

**Daedalus Wallet (Full Node)**
: Download and interact with the entire blockchain history without a third party.

**Yoroi (Light wallet)**
: Developed by Emurgo - this doesn't download a full history of the blockchain
 

---
## Landscape
---

Cardano creates global IT Infastructure for Financial and Social Applications and is building a decentralized application (DApp) development platform. Ultimately, Cardano is a global systems company.

### Industry Trends

Industry trends are outlined by the history of Cardano. The Cardano Roadmap explains the project through five eras - the fourth of fifth about to begin.

- [x] Byron - Foundation
    - Creating Ouroboros 
    - Transacting ADA
    - Wallets
- [x] Shelley - Decentralization
    - Building out Stake Pools, Delegating ADA
- [x] Goguen - Smart Contracts
    - Introducing the Plutus Platform
    - Interoperability with other smart contracts
- [ ] Basho - Scaling
    - Sidechains
    - Parallel chains
- [ ] Voltaire - Governance
    - Voting and Treasury

The developments within the past decade brought the first and second waves of adoption - going from first generation blockchain (Bitcoin), second generation (Ethereum) and finally the third generation which will bring mass global adoption and use cases are now at the cutting edge.


### Major competitors
    
**Ethereum** - Smart contracts, the second largest cryptocurrency by market cap

ERC20 is a scripting standard on the Ethereum blockchain used in creating smart contracts. 
ERC outlines six mandatory functions
- total supply
- balanceOf
- transfer
- transferFrom
- approve - verifies your contract works given total supply
- allowance - checks if one user has enough balance to send to someone else

According to Github data, Ethereum has 165 active developers per month, second in industry
Tezos - Smart contracts, proof of staked
    
**Polkadot** - Smart contracts using a similar Proof of Stake model similar to Ouroboros - the Cardano model. Clover is Polkadots version of creating cross-chain compatibility. "Polkadot’s vision is to build a web where people have direct control of their data. Polkadot, like
Cosmos, is a network of ledgers that allows the exchange of assets and data through ledgers. :

**Quant** - "Quant is leading this revolution. We’ve already developed Overledger DLT gateway – the world’s first DLT gateway for enterprise that delivers interoperability across different systems, networks, and DLTs. Now, we’re building on this platform to help enterprises, governments, and individuals, across the globe benefit from the true potential of an incredibly powerful technology."

**Algorand** - Founded in 2017 by MIT computer scientist Silvio Micali. They've already surpassed Visa in their transactions per second. Algorand has over 500 partnerships with seven companies working on the getting rid of intermediaries in the securities markets. 

**Ripple** - Ripple is a real time settlement platform that speeds up transactions and allows for global trading. It uses a network of validated servers rather than proof of work or proof of stake. Current partners include Standard Chartered, Deloitte, and the Royal Bank of Canada.

Additional competitors

- Waves - Partnering with Cardano
- Chainlink
- Lisk
- Qtum
- NEO
- Block.one
- Solana
- Binance
- Avalanche
- EOS
- F2

---
## Results
---

Cardano is creating transparent protocols to spark innovation, digital identity to five million students in Ethiopa, a smart contract platform for non-developers, and an updated financial/social system.

Decentralized finance (DeFi) applications are being built on top of the Alonzo mainnet and have been testing for over a year and hundreds of applications and NFTs will be available over the next year.



### Industry Core Metrics

- Acquisition 
    - Number and cost of new customers
    - App downloads
    - Wallet volume
- Activation
    - Montly active users and site traffic
- Retention
    - Active accounts vs inactive accounts
    - How long are people holding ADA
- Referrals
    - Social shares are measurable 
- Revenues
    - Daily revenue
    - Transaction volume
- Marketing Metrics
    - Which efforts attract customers - word of mouth
- Technical Metrics
    - Page load times
    - Dapps


Cardano's metrics:
- 3,000+ Developers trained in Ecosystem via Plutus Pioneers program
- 72% of Ada are delegated to stake pools
- Montly active Developers - 168, first in the industry.
- From November 2016 to September 2021, the Cardano library has published and peer reviewed 116 papers.
- Market Capitalization of 82 Billion
- Five million plus users on Atla Prism, the largest blockchain partnership ever

---
## Recommendations
---

I suggest Cardano integrates their software with Quant by creating an overledger with the Quant team. 

Joining overledger is comparable to giving your computer access to the internet. The overledger network is the world's first decentralized node service provider. Quant is an ERC20 token however it is blockchain agnostic and will likely be the one platform to connect them all. With the overledger gateways, anybody can use nodes within the Overledger system so Ethereum or Cardano or Ripple can use each others nodes to process transactions.

White Paper Overledger definition 
> Overledger can be described as a sorted list of messages which satisfy a set of unambiguous properties. A set of properties define the valid format of a message, how to build the fingerprint and other requirements dependant on the methods required. A transaction must contain the fingerprint of a valid message to be considered part of an Overledger application. The list of these messages defines what we call the Messaging Layer of Overledger. Another set of rules determines how to sort the valid messages in a sorted list we called the Ordering and Filtering Layer. A system using Overledger reacts to this sequence and can change its state. Any change in one of these sets of rules results in a different list of messages, or a different permutation. More systems, with different control logic, can share the same Overledger if they respect the same rules. "

![Overledger](https://user-images.githubusercontent.com/90283529/133914585-e92461fd-8eca-4ca8-ab8f-17d3fbc45d32.png)

Say Dennis and Randi have a smart contract

Dennis pays Y BTC to Randi only if Randi pays X Eth to Dennis. 

The filter looks for Randi pays X Eth to Dennis. When the message is seen, the BTC pays out and the BTC node will write the transaction on their platform.

<br/>

These technologies would allow Cardano to begin transacting with tokens without the need for an exchange. They need to connect themselves to the first mover in the space as it is unlikely to be taken over given it was created with security being the primary focus.

The point of this technology is to provide solutions for countries that have poor systems of recordkeeping - say property disputes, medical records - and digitial identity. Cardano took the open source route because they want to solve the issues, whether Quant, Ethereum, Tezos, or any company solves the problem, their mission will have been succuessful.

"In these places, the power to bundle a payment system, property rights, identity, credit and risk protection into a single application running on a cell phone is not just useful, it is life changing. The reason we are building Cardano is that we feel we have a legitimate shot at delivering — or at least advancing — this vision for the developing world."


Resources Used:
https://www.youtube.com/watch?v=FKh8hjJNhWc&t=129s
https://cardano.org/
https://emurgo.io/
https://iohk.io/en/
https://www.crunchbase.com/organization/cardano-foundation
https://en.wikipedia.org/wiki/Cardano_(blockchain_platform)
https://iohk.io/en/research/library/
https://docs.cardano.org/
https://github.com/input-output-hk/essential-cardano/blob/main/essential-cardano-list.md
https://developers.cardano.org/docs/operate-a-stake-pool/
https://roadmap.cardano.org/en/
https://www.investopedia.com/cardano-definition-4683961
https://docs.cardano.org/core-concepts/delegation
http://fc16.ifca.ai/bitcoin/papers/KLS16.pdf
https://www.youtube.com/watch?v=04D2BP33YI8
https://www.investopedia.com/terms/h/hard-fork.asp
https://www.investopedia.com/terms/s/soft-fork.asp
https://www.investopedia.com/tech/why-crypto-users-need-know-about-erc20-token-standard/
https://decrypt.co/80631/cardano-vies-ethereum-most-active-developers-reporthttps://decrypt.co/80631/cardano-vies-ethereum-most-active-developers-report
https://www.youtube.com/watch?v=Ww-sHCiRAzc
https://uploads-ssl.webflow.com/6006946fee85fda61f666256/60211c93f1cc59419c779c42_Quant_Overledger_Whitepaper_Sep_2019.pdf
https://uploads-ssl.webflow.com/6006946fee85fda61f666256/60211c93f1cc59419c779c42_Quant_Overledger_Whitepaper_Sep_2019.pdf
https://alpha.marlowe.iohkdev.io/#/
https://www.youtube.com/watch?v=APVwwkE72_s
