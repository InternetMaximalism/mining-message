Hi all,

We have just finished processing Claims. It took some extra time as we had to process transactions that occurred before the rules were publicly announced on October 10th. Thank you for your patience. Claims are now available on mainnet legacy. There's no need to rush - the rewards aren't going anywhere. We're also preparing Base rewards.

Despite having a 1 ETH cap, mining has exceeded 400 ETH per day and will soon reach a cumulative 10K ETH. This social experiment to incentivize Privacy Volume has been fascinating, and we can't imagine what will happen in 2 months.

First, we'd like to thank everyone who participated in the discussions. We need to continue discussing how to proceed with this social experiment and rewards system going forward.
I'd like to address some points for improvement:

The Hide and Seek game had too much freedom, leading to confusion from users less experienced with typical gameplay about what actions to take.
More users than expected used exchanges. While not too many did this, there shouldn't be an incentive to deliberately give up privacy that was gained, and it's not ideal that many users chose the more obvious hide and seek solutions.
Time information during withdrawals often compromises privacy, with many cases that should ideally be highly distinguishable (case 3). This can be resolved by centralizing and aggregating withdrawals, which we want to implement soon.

We are proposing several new mining plans that could be implemented in 1-3 months. These will narrow down hide and seek possibilities, enhance privacy, clarify user flow, and enable collaboration with other privacy protocols:

### Plan A: Privacy Summer

Maintain the current structure with minimal changes. Use on-chain voting to strictly nominate other Privacy protocol candidates and have users circulate through them. Users might receive multiple rewards as other privacy protocols may also offer rewards.

We're leaning toward Plan A, but would like to hear your thoughts on these alternative plans or any new ideas:

Plan B: Pooling
Users withdraw after a lock-up period using pseudorandom numbers generated from individual private keys and contract variables. No penalties for circulation.

Plan C: Asset Randomization
Users engage in hidden probabilistic contests within the contract, randomizing withdrawal amounts and asset types. However, forcing miners to participate in contests may have unknown impacts on liquidity.

## Q&A

>Hi team, what’s the purpose of listing the hub addresses? Is it a blacklist or a whitelist? Since almost all legitimate privacy protocols utilize a hub, it likely isn’t a blacklist. So, let’s assume it’s a whitelist. If that’s the case, does this mean that all methods or hub addresses not approved by the team are considered invalid? I don’t think the team can create an exclusive list of addresses/protocols that could help us avoid being flagged as “circulation,” as there are some methods on Base and L1 that allow us to avoid circulation without meeting the 30/30/100 criteria. Also, if it is a whitelist, using CEXes as a mixer becomes the simplest way to avoid circulation. Encouraging users to rely on CEXes doesn’t make sense. So, I’m unclear on the purpose of this hub address list as either a blacklist or a whitelist.  I also find this sentence unclear: “This criterion covers almost all addresses with indirect traceability.”  I thought the aim of the “game” was “hide and seek,” where the rule is “don’t let others link the deposit and withdrawal addresses.” However, there seem to be many hidden rules that could suddenly make us invalid or penalized.

The hub address list is a whitelist just not to make mispanalties. In some cases, there are CEX addresses which do not have 20 incoming || 20 outgoing addresses.
Basically, we and the community already decided not to make penalties without a notice and enough discussions.

> Are there any dApps other than Tornado that are blacklisted from an AML perspective?

Actually, it depends on the AML API side, and we don't know everything about it. So far, we confirmed TC/Railgun are highly scored.
By the way, if a user can provide the "proof of innocence" of Privacy Pool, we guess the protocol can welcome the fund from these in the future.
