---
description: >-
  Note: Before the system was upgraded to BTC Layer2, the consensus algorithm
  ran live and was 100% secure with a TVL of 130M USD.
---

# 👮‍♂️ Security Mechanisms of RPPOM

RPPOM possesses an extremely high level of system security, sufficient to defend against various malicious attacks and unexpected situations, ensuring the safety of the network and assets. We can also guard against the following extreme scenarios:



**1.** The Citizen plays a crucial role in maintaining system stability. Suppose a randomly selected portion of Citizens doesn't work; as long as not all of the selected 25 Citizens are inactive, it won't affect the chain's stability. As long as one of the 25 selected Citizens is online, it can produce 25 consecutive blocks. In such an extreme abnormal situation, relying on the chain's incentives can still transition to the next adjustment round. Under normal circumstances, if a Citizen fails to produce a block consecutively 5 times, their participation rate will be reduced. The participation rate will decrease the Citizen's staked asset amount in a coefficient manner, with the formula being: the Final Staked Amount Assets from Ligo network by Citizen = User Staked BTC/Ligo/iGo Amount x Participation Rate (0\~100%). Therefore, all Citizens will eventually be high-quality nodes, and the above extreme scenario is unlikely to occur in real-world settings.

**2.** Suppose a Citizen maliciously produces two different blocks at the same time. Subsequent Citizens will continue to produce blocks based on the order they received. When the block production round ends, the Ligo Layer2 will automatically switch based on the length of the two chains, choosing the longer one. In such a scenario, ensuring a confirmation count of 17 blocks can prevent double-spending attacks.

**3.** Suppose a mining pool occupies many resources on the chain but less than 51%. In this scenario, even if the mining pool's asset allocation is perfect, it cannot guarantee that it will have more than 50% of the block producers in each round. Therefore, based on a confirmation count of more than 17 blocks, it's challenging to execute a double-spending attack.

**4.** Suppose mining pools collectively occupy more than 51% of the resources. In this extreme scenario, the mining pools could potentially cause a data rollback on the chain. However, the assets of the mining pools are not just one single assets  but also many Ligo network staked assets, which are managed by Senator consensus. If mining pools collude maliciously, they will face the following situations:



_(1)_ The participation rate of all mining pools involved in the malicious act will be reduced to 0%   (meaning no matter how much they stake, it's equivalent to zero).



_(2)_ The sssets staked by the mining pool will be frozen and restricted. Whether they are unfrozen depends on the impact caused. Malicious actions mean that mining pools will face the loss of registration fees and their assets staked in the pool. Users supporting that mining pool will need to enter an appeal process, with the Senator consensus deciding whether to unfreeze the user's assets.



In conclusion, under the protection of the RPPOM consensus mechanism, the potential benefits and risks faced by Citizens acting maliciously are not advantageous.
