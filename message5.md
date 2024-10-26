Hi, miners!!

The protocol has made 5000 ETH in cumulative total, thanks for your support for the project and your contribution to privacy. 

The suspended claiming is now on process, finalizing the eligible amount for each and making sure there's nothing wrong.

In terms of rules and criteria for slashing, we were asked to state them exactly. We added them to the documents, and also state here as well.
The circulation part and rushy deposit part is just adding the exact functions of the tracers.
This statement regarding hub addresses is less strict than what was described previously (the recommendation of using privacy dapps), so that nobody makes less rewards than he/she expected from the documents.

[Circulation] Circulations include greater circles not limited to 1 hop or 2 hops. Let's call addresses, which have many incoming/outgoint transactions among many addresses without a link between incoming fund and outgoint fund in one transaction, "hub address". Avoiding circulation requires to have a hub address to come back to the contract.  

[Hub Addresses] We list the major dapps and CEXs on mainnet and Base, these dapps are widely classified as hub address, and all the addresses with more than 30 depositors & 30 withdrawers & 100 ETH balance will be classified as hub address as well currently.  
This criteria covers almost all addresses with indirect tracability.
 
[Rushy deposit] Any transaction in any sequence of more than 3 transactions in 4 hours will be flagged as a rushy deposit. Making more than 5 rushy deposits will make your whole a deposit cycle "case 3".

And we need to report you guys that the network went down for about a hour because of AML API's problem, and some issues of the CLI side coming from that problem took 6 hours to update until the new version(1.1.3) release.
It does not affect on any rewarding policy. If you have any problem now, please update your CLI to 1.1.3.

## Q&A

>I still don't understand why < 30% funds can be back to the deposit address from the withdrawal address while linking the W address to the D address is strongly prohibited.

This is all about preventing suicide attacks. If it's 0%, anybody can ruin your entire rewards just by sending $0.1 to your deposit addresses, then it should be more than 0%. 30% of deposit is a cost to do that suicide attack now.

>not sure the protocol uses "innocent until verified guilty" principle.

This is the principle of the game.  
Right now, the protocol just automatically seeking the players who are out of the rules. Even if they are guilty, they'll get rewarded as innocent players.
Even after introducing quiz protocol, this principle goes on, but suspects need to prove that they are innocent players by ZKP when they acccused on chain.

>I am curios
During the time when the error happened my deposits failed about 4 time. does that mean I will get no rewards for those 4 deposits?

This does not change rewarding policy, and the cancelled deposits will be ignored. 1 hour network issue and 6 hours client side issue is rather limited to the 2 weeks rewarding period.
Thanks for your comprehension.
