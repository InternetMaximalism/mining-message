Hi, all. Thanks for staying in the loop.

Q&A

>This is almost a tax on mining. I don't believe that this happens and devs should not implement this.

>Before talking about "the tax," the treasury is not needed for anybody.

We are glad to hear that opinion. That's the reason why we publish this topic in the hackmd page, the most findable place, to discuss about this. 

The important thing of crypto in general is that the mining/token distribution should have competitions as a game to be sustainable and the product part should be strict for PMF.
We can't see any token distribution sustainable without a fiar competition. And, Bitcoin is very sustainable since it has a competition of PoW while it has huge electricity comsumption.
How to make the game good for product developments/the ecosystem as well is a very difficult part. Let us think together. We intended to set the treasury as a sustainability machine.
One thing we can assure you guys is that we don't go this treasury issurance without the agreement of the community.

>The fact that 11 addresses, with no signs of participating in privacy mining, hold a large amount of ITX tokens is a bigger issue. While we are told that circuit verifications can be confirmed, it’s clear that these addresses have not engaged in any activity other than receiving ITX tokens. The team has an obligation to clearly explain why these addresses were able to claim the tokens.

It's us. As we described [here](https://hackmd.io/zNLtkMXXSCernbkTf1BTrQ?view#The-history-of-this-mining), we were mining from the beggining.
We publish this mining with detailed introductions on the github organization top page in August admitting the risk of the competition, but there was no competitor at that period actually. We also pinned and tweeted.
We don't know if people could call this premine or if people don't call this premine because it was published to have potential competitions, but we secured almost 30% of the max supply by the mining.
The large part of that 30% will be donated to the treasury, so we don't keep all of them. Let us publish the detail including the locking period soon.

All the token cames from mining. No exception. It should not be so linkable actually and it's using zkp to unlink it from a withdraw address since the reward amount can make many information to reveal the deposit.
But this time, the CLI should have been simple to use. That's the only the reason why the withdraw address is the claim address in today's CLI.

>but it is obvious that after INTMAX reaches TGE

The ERC20 is not transferable now. We don't think that it's TGE in a legal sence. It's a point now.

>many crypto critics will discover and condemn this opaque system
>The INTMAX team should seriously respond to the criticisms and questions from us, the supportive early adopters, and prepare for real criticism. 

Yes, huge thanks for this discussion. This system is not opaque, but the document was. The problem was that we prioritised the invitations to this mining 
since the halving was close. And we expected that just following CLI's guide would make people follow the protocol rules, that was not true as we could see in the result. It was our duty to invite many people in privacy spaces to this opportunity. We intended to make the doc simple not to confuse you guys, but seems actually it did.
Only the opaque part of this system is the treasury issurance which is not decided. Nothing else.

>The 'message' response is insufficient and will not satisfy them.

This is the best way to log discussions so far. It's hard to scroll the discussion in discord, and it's also edditable/erasable.
We can copy and paste to post the answers if it's really required.

>for "multiple deposits within 4 hours", if we simply let CLI do its job, are more than 2 deposits within 4 hours theoretically really impossible even if you were to draw a rare random number consecutively? if Deposit 1 -> sleep 1 -> Withdrawal 1 -> sleep 2 -> Deposit 2, sleep 1 + sleep 2 < 4 hrs does look possible. Or you meant multiple deposits within 4 hrs ON AVERAGE?

"multiple" was not a correct word, and this part remained opaque in the document. Our applogies. We updated the doc and keep updating it.

--
[Added on 15.10.2024]
--

Hi, all.
We'll do everything we can do for those who were just using the CLI even if there were some unexpected issues.
We once stop finalizing the reward tree to deal with this so that the reward distribution will have some delay. Thanks for the comprehension.

> I believe early supporters here are eligible for such a treatment as an "amnesty period”

What we can do is to ease the border line or some parameters like, the penalty for 5/10 concentrated deposits => 7/10 is still fine. We don't change the code itself since it's not so easy to change the structure which was done while ago. Also we don't think it has enough legitimacy to change the code or the structure itself. There's something we can never be tolerant to like 10/10 is deposited in a hour, since it's very hard to think it's unintentional.

>I just went through the update and I'm wondering if case 3 will be punished for the past weeks?

We will significantly ease the border line of case 3 like described in the previous comment.
1. The penalty on concentrated deposits don't be applied if it's less than 8/10
2. The penalty on half-way deposit (1/10~9/10) will be eased.
are under a discussion. The many of incidents classified as case 3 will be saved at this time.

>The past cases should not be penalized retroactively except in cases that clearly don't contribute to privacy, such as case 4.

Actually, the most of cases of cases 3 don't contribute to privacy or the anonymity set because they are highly distinguishable.
So making no-reduction for all case3 cases is an unacceptable idea. We might as well throw away all of this system if we allow that. But the many of case 3 should be saved since the CLI guidance without the detailed docs did not work this time.

>I have done mining on my personal laptop and I think I’ve got penalized for case 3 because I have to reboot the CLI every time I move physically from one place to another.

Yes, we took time to realize this problem. We did not find that sleep and reboot makes short time depositing. Our apologies. 

>Which is it?  Point farming/airdrop or a serious coin mining like BTC, LTC, and XMR? 

It's a difficult question. If it's allowed, we would like to say it's middle now. What we want to make is automatic rewards for contributions to privacy, and you can call it point farming in a sence since many point systems are automatic. But, in that sense, it differs from airdoping.
It has competitions and works like PoW, and that's why we call this mining.

>1 - It is very didactic the way the information has been put in order to be able to configure the networks and fundraising in eth well to use in the base.

>2 - In terms of the alchemy material, I think we could improve the delivery of information in the registration section. When registering, there are some screens that the user has to configure, such as: type of activity, which is not mentioned in the manual. I had to ask Vi, because I didn't know if this would have an impact on the configuration model sent in the manual as a printout. And at the end, inform them that they will only be on the api key screen and will not do anything else from there, just get the info and inform the mining terminal. 

>3 - I believe that if videos of the process are included in the manual, it could be more didactic and easier to operate the whole process.

Thanks for your precious feedback. We consider courteous guidance and display on the CLI. Indeed, the alchemy part is the part where the user stumbles more than the CLI itself. 

