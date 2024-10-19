Hi, miners. 

After a week of discussions, we have reached a conclusion regarding the application of the unpublished rules. Thank you to all the miners who participated in the discussion, including 0xprv, dc48, Zeus, JohnDoe, and others.

We have decided to withdraw and not apply these rules to activities that occurred prior to their publication　completely. This application not only goes completely against our and the community's values but would also make this game of privacy to a disorganized airdrop. We believe that the process of this discussion and its conclusion were necessary to maintain future rules, implement safe changes, and establish a strong culture where miners and users can trust these processes.
We are withdrawing many of the points written in message3. 

Originally, while the technical purpose of this game is to participate in and maintain a steady number in the anonymity set, in a broader scope, this is about enabling collaboration without negotiation, as seen in many mining systems. Although this game has generated many negotiations this time, we believe these should be minimized going forward. We will work on creating an environment where miners can focus more on the game.

Additionally, due to technical difficulties, we are unable to create an overlapping deposit period between L1 and L2. Layer 1's main contract deposits will stop at 19th UTC 00:00. Regarding this, we will also completely remove penalties for half-way deposits in deposit cycles that began one week prior, to avoid changes in rewards. One week has been stated from the beginning as the reward generation interval and is a sufficiently safe deposit cycle period. Withdrawals can be made at any time.

Specific policies are as follows:

1. Complete cessation of Case 3 application to all activities from and including 10 days before publication
2. Not applying half-way penalties for deposit cycles that began after 12th 0:00

After the move to Base on 19th 0:00, please update your CLI to a new version.
Guide: https://hackmd.io/g1Pl9rQAQMmC86I7wiMEtQ

## Answers to questions

> Hello. We are pleased that the team has shown understanding for us and would like to express our thanks for the detailed replies.

>  ::the circulation and the highly distinguishable deposit was prohibited as the rule

> We understood these rules. But we still thought our rushy deposits would not be highly distinguishable because many other miners already made rushy deposits. Being rushy makes us distinguishable only when there are no rushy people, but once there are, a newly added rushy person is no longer distinguishable. This was our thought, and we believed we wouldn’t break the rule. Of course, we now understand that the degree of the anonymity goes down when there are two types of behavior in one anonymity pool. However, at the time we thought that was part of the game.

This is a very interesting topic, let us explain in detail.
At first glance, rushing seems fine when there are many rushers. But, if one acts very rushy to do instant deposit and withdraw, it's distinguishable. So, to be indistinguishable, you need to have enough possibility that other rushers or usual people withdraw funds in the period from your depositing to your withdrawing. People are economically incentivised to act extremely rushy without forced random periods. That's the reason why we need a random period to wait. Essentially, if we can have the randomness on the withdrawal side, it's fine. But we cannot verify that on the withdrawal side since it's private. If we use zkp to prove a deterministic period to wait coming from a private key & a block header, we can verify it without deposit-side randomness. Anyway, in any case, rushy deposits are basically distinguishable.
