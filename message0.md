Hi, all. thanks for participating in the anonymity set.

Today we are adding more specific mining rules to the current abstract document [hackmd](https://hackmd.io/zNLtkMXXSCernbkTf1BTrQ).

We will also answer questions from the community later in this GitHub page.  I will also summarize here the issues we currently wish to discuss with this community. I'd like to hear what you think about these!  

1. Collaboration between Volume Oriented Strategy and other privacy protocols 

Projects that are only interested in volume can collaborate with other privacy protocols that are TVL oriented. In order to mine the same fund repeatedly in this privacy protocol, it is necessary to play a hide and seek game. In other words, using other privacy protocols is the key to winning the hide and seek game.  

2. About Treasury 

We are considering the use of treasury with decentralized governance by token holders. In order to increase this treasury fund, we will introduce fees in the future, and most recently, an allocation from the mining reward to the treasury. 5.  

3. Prevention of scams 

All documents must have a link to this github organization. All documents without a mention from this github should be considered scam. 6.  

4. Use of Layer 2 

We understand that the current CLI and contracts are immature in terms of gas efficiency when it comes to getting more users to create privacy. Which would be best?

## Response to the question.  

> Does this work on mainnet right now? Should I start from a testnet?  

A: There are no rewards attached to testnet, it is purely for security checks. It is of course possible to deposit directly to mainnet from the beginning, but the cautious should try testnet.  

> I got blocked for my IP. then I changed my IP to another one by using VPN; now it doesn't get blocked. i can continue mining and get rewards, can't I? I can continue mining and get rewards, can't I? 

A: IP blocking is done for IP addresses that are under sanctions such as North Korea, etc. USA is blocking them for other reasons. IP blocking is flexible and we cannot guarantee anything. We cannot guarantee anything as IP blocking is flexible and the use of citizens from all IP blocked regions is strongly discouraged in this system. 

> Is there anything to read about that mechanism? 

 A: Please see the AML section of [hackmd](https://hackmd.io/zNLtkMXXSCernbkTf1BTrQ)

> As I understood withdrawal time randomized right?  

A: It is randomized, and non-randomized interval deposits are easily identifiable, so there will be no rewards. Please note.  

> Just curious if I need to privately send my partners some ETH or USDC could it work with you?

A: You are very welcome to explore the various use cases of the protocol with the understanding that we are not a money transfer business. 

> If I mannyally set my value to the env.miainnet.json , is it eligible ?  

A: If this value is different from other participants on the protocol, it is more likely that you will not receive the reward. The important point is that all identifiable fund combinations will receive slash. 

> “ERROR: Serialization error: failed to parse response: error decoding response body: data did not match any variant of untagged enum CirculationResponse “what is this ? and how can I avoid this ?  

A: This is an error that occurs when the software receives an unexpected response on a communication required for mining. Many of these have been addressed in the latest version, so try restarting the latest version. If that doesn't fix it, try setting the API key for a more common node service such as alchemy or infura. 

> Don't you think gas cost is too high to mine on L1? It costs a lot  

A: The gas cost with Layer1 is indeed high. We know that this makes many users hesitant to create privacy. We plan to support Layer 2 as soon as possible.
 
> Q: What actions will disqualify me from receiving ITX token rewards?   

A: All identifiable withdraw/deposit combinations will be subject to reduction. All identifiable withdraw/deposit combinations will be subject to reduction, as will any minings that do not contribute to privacy, i.e., circulation type2. We have decided to write more about this in [hackmd](https://hackmd.io/zNLtkMXXSCernbkTf1BTrQ). Please take a look.

Added on 10.10.2024

1. Many ppl are sending money from "withdraw address" to "deposit address." It makes the reward 0. Please don't.

2. Many ppl are customizing the CLI software to make the interval short, but it reduces the reward significantly. We strongly recommend use the CLI normaly, bc all distinguishable transactions will be slashed in this system, and the CLI avoids that probelm.

>Are deposits are randomized by the sleep time and can changing the sleep time be regarded as manipulation?

A: It's hard to make a regular interval with a sleep condition. If restarting the cli makes rushy deposits, there can be a problem in a rewarding process. The next version needs that patch. 

>does anyone know more about "randomized interval deposits"? I don't know what can be "non"-randomized deposit/withdrawal coz it's controlled by the software and the protocol.

A: "Non-randomised" means a constant interval like every deposit interval is 1 hour or being too rushy in a short period like <10 min.

> what we do if we cannot send it back to exchanges after withdrwaing ETH from Intmax? just leave it there or use other privacy protocols?

A: If sending privacy ETH back to an exchange makes certain distinguishability, 2/3 of your reward will be slashed. There are 3 options to avoid it
1. Using this protocol again not for rewards
2. Using another protocol
3. Just waiting for 3 months
But, anyway, withdrawn ETH is private ETH. Why do you want to redeposit it to exchange to ruin it?
