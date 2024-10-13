Hi, guys!
Thanks for stay in the loop literally.

We are very happy to see much EOL (private $ETH) is being produced.

After a serious discussion about the problem of too much gas fee to mine, we decided to move to Base for a couple of months.
The move will happen next week. We believe that this makes the anonimity set and the amount of Ether of Liberty(EOL) greater.

Actutally the mining is a part of the entire picture, and the main product is a stateless layer2 which has extreme scalability and privacy. Of course, the next phase of the mining will be with that.
It's a bit tantalizing that we need to move to another layer2 before launching it.

Regarding the mining rules, the first principle is "don't make any association between the deposit address and the withdraw address."
The game is almost defined with this part. That's the reason why depositting the biggest money is not always efficient. The bigger amount can make this association to make your reward smaller.

The second principle is not to make an obvious circulation. This one makes another game, "hide and seek", described in the [hackmd](https://hackmd.io/zNLtkMXXSCernbkTf1BTrQ)

About the structure, we hope this picture helps

# Answers to Questions

> Does this mean 50% of the current mining rewards go to the treasury if the 2nd halving took place on Sep?

A: It does not mean that 50% mining rewards go to the treasury since it's the additional issurance, but it means that 33% =50/(100+50) of the issurance of this period between halvings will go to treasury. It's under a discussion as follows.

>Why do you impose Treasury issuance only after 2nd halving, not from the beginning?

A: It was not set in these periods, and this lack will be compensated by the donation from the miners of these periods. 
We were planning that donation and it was not the protocol-level, that's the reason why we described that the protocol-level additional issurance is after the 2nd halving.
But, actually, before the 3rd halving we have more time to discuss on this point. Unlike talking about the circulation penalty, this point is all about the culture.
The greater number of miners we have, more meaningful the discussion it becomes. And, feel free to discuss about this on the discord involving the other miners since it'll be hard to change after once it's fully decided in this period before the next halving. 

>https://etherscan.io/token/0xe24e207c6156241cafb41d025b3b5f0677114c81#balances
>What are these addresses holding large amounts of the same number of tokens? These addresses show no evidence of participating in anonymity mining. How did they acquire such a large number of tokens?

All the token issurance is coming from the mining without any exception, and you can see that all of the minter contracts have circuit verifications.
In this section, you can see the contracts from the beggining.
https://hackmd.io/zNLtkMXXSCernbkTf1BTrQ?view#The-history-of-this-mining

> — In general, am I still eligible to continue the mining process, and how do I ensure the progress of the two deposits that have already been used is preserved?

A: Please use the same deposit address in general. (In your case, you already sent money from the withdraw address to the deposit address so it's difficult this time.) 
And you can ensure that your mining is happening by Etherscan or the CLI. We admit that the precheck function is needed in this CLI to have more automatic guidance to check if your mining will be effective.

>— The terminal generated a new deposit address. Is there a way to transfer the remaining funds directly to this new address from the previous one, or must I first export them to my withdrawal account and then deposit them again into the new address? 

A: Plese don't make any relationship between the withdrawal account and new/old deposit accounts.

>— And this new address is something I should use now or another one should be generated in the sake of security?

A: We highly recommend to generate a new key for the withdraw address. Only the rule of this mining game is how not to make a relationship between these addesses. This game is rulewise simple but a bit difficult to win the others.

>—  Can I continue using my previous withdrawal address in my wallet to receive deposits and claim tokens once I’m done, or do I need a new one?

A: "receive deposits"... From the protocol contract, yes, but sending money on L1 by yourself, no.

>— Where can I find a complete list of rules that could lead to disqualification? My funds are legit, and I’m not using a VPN or anything like that, so I don’t believe I’ve done anything wrong. I just want to be sure this doesn’t happen again.

A: We admit that the rule was not enumerated while it's clearly stated. The hackmd doc will be upgraded within 24 hours. As we said above, the software should have more automatic detections if any action is against the rule, 
but it can not prevent all of them. We make the software to make ppl gain rewards if they act usually with ordinary amounts of deposits. This should be somehow guaranteed. 


