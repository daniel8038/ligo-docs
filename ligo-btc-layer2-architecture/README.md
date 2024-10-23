---
description: LIGO BTC Layer2 Blockchain = Bitcoin + RPPOM Consensus + BVM
---

# 🌎 LIGO BTC Layer2 Architecture

Ligo Layer2 is a Bitcoin L2 Blockchain based on Multi programming language supported VM. It moves the computation of new Bitcoin protocols, such as BRC-20, to L2, making it a decentralized computing chain for Bitcoin. As a Bitcoin L2, Ligo operates as a blockchain that utilizes the RPPOM (Random Pool Proof of Multi-properties) decentralized consensus algorithm. This stochastic multi-asset equity pledging consensus algorithm allows decentralized mining pools to operate. The computation results are then stored as Merkle Trees and smart contracts, and the block state is finally written into the Bitcoin block as a witness to complete block generation. Validators are responsible for challenging the correctness of the block, submitting fault proofs for problematic blocks, and obtaining challenge rewards.

LIGO L2 Technology Architecture

<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

**3.1 Consensus**

&#x20;       Ligo Layer2 combines the BVM and RPPOM consensus algorithm to actualize a decentralized Bitcoin L2. This chapter will explain the RPPOM consensus and the three roles within the ecosystem: Senator, Citizen, and Tourist.

**3.1.1 RPPOM Consensus**

According to the RPPOM consensus mechanism, the Ligo Layer2 network produces a block every 5 seconds, significantly improving transaction confirmation speeds. This efficiency is evident when compared to BTC, which produces a block every 10 minutes. Thus, the performance of a BTC asset transfer or trade on the Ligo Layer2 network is approximately 120 times faster than that on the BTC network. RPPOM's theoretical TPS (transactions per second) reaches 10,000-30,000, sufficient to handle high-load transactions across multiple chains.

The server and network requirements for Ligo Layer2 are less demanding, more adaptable, and can easily interface with other blockchains. Furthermore, the Ligo Layer2 generation node is randomly selected from all Candidate Citizens who meet the pledging requirements. This selection process randomizes the generation nodes, making them difficult to target, thereby greatly mitigating the risk of network attacks. Even a complete attack on partial nodes won't affect the stability of the entire network.

There are three roles in Ligo Layer2: Senator, Citizen, and Tourist. The system will have 15 fixed Senators, all with identical permissions but different categories. Five of them will form the House of Lords, and the remaining 10 will form the House of Commons.

With the integration to SINOHOPE MPC, the Role ARCHON added as additional security enhancement, please refer to the diagram explained in the following section.

The consensus of 15 senators decides on the ARCHON, who liaises with the MPC of SINOHOPE, facilitating the asset recharge on the blockchain. When a user requests a withdrawal, it requires the consensus approval of the 15 senators. If approved, the ARCHON of SINOHOPE will process the withdrawal request. If an audit reveals that the ARCHON is engaged in fraudulent activities, the senators can replace the ARCHON through a new consensus

We will first outline the details here:

_Let R, = Zx]/f(),where f(x)is a polynomial of degree n. The public parameter is A% e R!x(m-1)andis used to commit to a scalar message m C Dom C , where Dom is a domain of that message, asfollows: Com,.(m, S) = A% · S + m. The properties of the homomorphic operations are also defined as:_

_Coma(my, S) Coma(mz, )= Coma(m, S)+ Coma(mS)mod q=Coma:(mi +m2S +S)mod qComa(mi, S)_

_Coma;(mz, S)= Coma(m, S)- Coma(m,S) mod q= Coma(m - m2,S-S)modq_

_wherem;, m, E R, areringelements and S, S e R-xl are (m - 1)-dimensionalvectors ofringelementsThe integers m;, m, E Z are encoded in binary as coeficient vectors m, = (m;o .., m;-0,...0) e (0,l)' (my 2') with m;y e {0,1} and j e{0,1}._



**3.1.2 Senator**

A Senator is an asset manager and community administrator in the L2 ecosystem. By consensus, the Senator is responsible for managing assets on hot and cold multisignature addresses on different chains. The cross-chain interconnection must ultimately be conducted through the Senators' consensus. To become a Senator, a user must pay a certain amount of $LIGO tokens, ensuring a significant financial stake is placed in the system. This financial stake safeguards the network's integrity and stability by aligning the Senators' interests with that of the network. The change of Senator is determined by Citizen votes. By pledging, Citizens are selected to produce blocks and obtain block rewards. Tourists can also participate in mining and receive mining rewards by pledging assets with Citizens. According to the RPPOM consensus mechanism, after new blocks are generated, the system will automatically follow the underlying protocol and distribute rewards to citizens and their supporters (users who pledged their assets with Citizens), according to their weighting.

**3.1.3 Citizen**

&#x20;         A Citizen can be understood as an on-chain mining pool that requires the installation of full node services to gain relevant weights through asset voting. The higher the weight, the greater the probability of obtaining blocks, and there will be rewards for block generation.

**3.1.4 Tourist**

&#x20;        A Tourist can pledge transferred assets to a Citizen to obtain relevant rewards. If the pledged Citizen successfully issues a block, profits will be obtained based on the proportion of the pledge, with Citizen's handling fees being deducted.

<figure><img src="../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>
