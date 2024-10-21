Hi, miners. 

After a week of discussions, we have reached a conclusion regarding the application of the unpublished rules. Thank you to all the miners who participated in the discussion, including 0xprv, dc48, Zeus, JohnDoe, and others.

We have decided to withdraw and not apply these rules to activities that occurred prior to their publication　completely. This application not only goes completely against our and the community's values but would also make this game of privacy to a disorganized airdrop. We believe that the process of this discussion and its conclusion were necessary to maintain future rules, implement safe changes, and establish a strong culture where miners and users can trust these processes.
We are withdrawing many of the points written in message3. 

Originally, while the technical purpose of this game is to participate in and maintain a steady number in the anonymity set, in a broader scope, this is about enabling collaboration without negotiation, as seen in many mining systems. Although this game has generated many negotiations this time, we believe these should be minimized going forward. We will work on creating an environment where miners can focus more on the game.

Additionally, due to technical difficulties, we are unable to create an overlapping deposit period between L1 and L2. Layer 1's main contract deposits will stop at 19th UTC 00:00. Regarding this, we will also completely remove penalties for half-way deposits in deposit cycles that began one week prior, to avoid changes in rewards. One week has been stated from the beginning as the reward generation interval and is a sufficiently safe deposit cycle period. Withdrawals can be made at any time.

Specific policies are as follows:

1. Complete cessation of Case 3 application to all activities from and including 10 days before publication
2. Not applying half-way penalties for deposit cycles that began after 12th 0:00

After the move to Base on 19th 0:00 UTC, please update your CLI to a new version.
Guide: https://hackmd.io/g1Pl9rQAQMmC86I7wiMEtQ

## Answers to questions

> Hello. We are pleased that the team has shown understanding for us and would like to express our thanks for the detailed replies.

>  ::the circulation and the highly distinguishable deposit was prohibited as the rule

> We understood these rules. But we still thought our rushy deposits would not be highly distinguishable because many other miners already made rushy deposits. Being rushy makes us distinguishable only when there are no rushy people, but once there are, a newly added rushy person is no longer distinguishable. This was our thought, and we believed we wouldn’t break the rule. Of course, we now understand that the degree of the anonymity goes down when there are two types of behavior in one anonymity pool. However, at the time we thought that was part of the game.

This is a very interesting topic, let us explain in detail.
At first glance, rushing seems fine when there are many rushers. But, if one acts very rushy to do instant deposit and withdraw, it's distinguishable. So, to be indistinguishable, you need to have enough possibility that other rushers or usual people withdraw funds in the period from your depositing to your withdrawing. People are economically incentivised to act extremely rushy without forced random periods. That's the reason why we need a random period to wait. Essentially, if we can have the randomness on the withdrawal side, it's fine. But we cannot verify that on the withdrawal side since it's private. If we use zkp to prove a deterministic period to wait coming from a private key & a block header, we can verify it without deposit-side randomness. Anyway, in any case, rushy deposits are basically distinguishable without a long randomized period of withdrawing.

### Added on 21th Octorber

Sorry for the delay of claiming. Applying the result of discussion above takes a bit, 1 or 2 weeks. 

>hi, just out of curiosity, does linking withdrawal addresses directly/indirectly make us ineligible for the rewards? for example, I can easily detect all of these withdrawal addresses belong to the same person, but I cannot tell which deposit addresses are associated with them. is this guy still eligible for the reward? considering it is effectively the same as continuing to use one withdrawal address, not subject to a penalty?

![image](https://github.com/user-attachments/assets/86915493-74ff-4f5b-b381-8b87caf0bd56)

This point was a biggest discussion in the team, and originally the team intended to make all the withdraw addresses are different, like 10 deposits make 10 withdraw addresses. But we expected that people will bind them all anyway. So what you pointed out already happened.

When it's a distinguishable amount to correspond to a set of deposits which originally comes from one address, yes, it should be banned. But the current program is not banning that. Actually this is the only the way to ban the huge amout mining done by a super rich, and let us propose the plan to ban this.  
Introduction of "quiz protocol" 
1. finding and proposing a combination of withdraws and deposits (manually or automatically)
2. proposing the combination onchain
3. the widthdrawer needs to prove that the specified withdrawn money is not coming from the deposit by ZKP.

We are planning to propose this to the community to introduce this 1,2 months later. Let us add this to the document.

> how do you punish the withdrawal address based on the behavior of the deposit address when no one knows which withdrawal address is associated with the deposit address? I mean, if I use address A as a deposit and address B as a withdrawal and break the rule by doing rushy deposits from address A, how the team/the protocol knows address B should receive no/much less rewards? or it's not about rushy deposits but about rushy withdrawal indirectly?
>the rewards are per deposit but the withdrawal address claim the rewards.

The rewards and the punishments are on deposit side, and the program traces withdrawn funds only when it can correspond and trace. You maybe feel you have rewards with a withdraw key since the deposit key is coming from the withdraw key. The key are coming from the same thing. The withdraw address is separated from a claim address in the contract(the protocol), but the program uses a deposit key to claim and issues the token to the withdraw key now not to make confusion to selecting a claim address. 

>Explain, I don't understand why I should give the private key and not the public key? This is basic security - do not share the private key with anyone

Yes. And you are not giving a key to anybody. It's non-custodial. Importing a key to a node program is really normal while we admit that not so many people of current miners have experiences of that. Welcome to the new world.

>What I will be appreciated for if team could give us updates in Discord not just in GitHub. 

We expected that it would work by just publishing on Github. But ok, we can send somebody from the team.

>Usually, there is onchain governance, and there are forums and foundations, but it is not making sense to vote anonymously on Discord, and if miners are voting, their addresses will be known... I am quite curious about how these project people are planning to be moving forward?

Actually, we have no plan for that point. What do you guys think?
And one thing we are thinking is the discussion policy of the rules.
1. The introduction of rules will be at least 2 weeks after noticing the proposal.
2. It requires the full discussion with the discussion contributors. 

>how can i keep privacy after withdrawal. i wanna reuse the eth in withdrawal address to next cycle. give me a tip

We added the usage of dapps and the recommendation about CEX in this document.
https://hackmd.io/zNLtkMXXSCernbkTf1BTrQ


