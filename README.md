# gate launchpool: how hourly staking airdrops work, what the headline APR actually pays, and how to join with coins you already hold

Most people who type "gate launchpool" into a search bar are holding crypto they aren't using. A stack of USDT sitting in a spot wallet, some BTC waiting for a price target, GT bought months ago. The question behind the search is usually the same: can I earn on that without selling it?

Short answer: yes, and the mechanism is more specific than most summaries make it sound. The longer answer involves an hourly reward formula, a trading-volume rule that decides how much you're even allowed to stake, and APR figures that can look like typos. Worth walking through properly, because two of those three things decide whether the round is actually worth your capital.

## What Gate Launchpool actually is

Gate Launchpool is a staking-based token distribution product. You commit a specified asset into a campaign pool, and the pool pays out a new project's token to participants on an hourly basis. Your staked asset stays yours and stays counted toward your account's holdings.

The product isn't new. It ran as Startup Mining until January 2025, when Gate renamed it to make the model clearer: stake assets, earn new-project rewards. It lives in the same area of the platform as CandyDrop and HODLer Airdrop.

The part that trips people up is this: Launchpool isn't one product with one set of rules. Each round sets its own reward pool, its own supported stake assets, its own per-user staking cap, and its own participation requirements. A round might open USDT, GT and project-token pools. The next one might use BTC, ETH and GT. Nothing is permanent, so the current round page is the only authority that matters.

Two consequences follow from that. You can't assume the asset you want to stake will be accepted in the next round, and you can't assume the cap that applied last time still applies.

## The hourly reward formula, minus the mystique

Gate pays Launchpool rewards every hour, not at the end of the campaign. The official formula is short:

> Hourly staking reward = (your effective stake over the previous hour ÷ the pool's total effective stake) × the hourly reward pool

"Effective stake" is where it gets slightly technical. The system takes multiple snapshots of your staked balance inside each hour and uses the average, not your balance at any single moment. If you stake right before an hourly payout and the snapshot average is low, you get less than you might expect from glancing at the number in your wallet.

Because allocation is proportional, Launchpool isn't first-come-first-served. Joining on day three of a two-week campaign is fine and you'll still earn. What you won't get is the same share as someone who was in from hour one, because the pool's total stake has grown by then.

Each pool also carries its own per-user hourly reward cap. Once your rewards for that hour hit the ceiling, staking more stops helping for that hour. The cap differs by project and is published on the round page or its announcement.

## The 60-day volume rule, which decides how much you can stake

This is the piece most write-ups skip, and it's the one that quietly determines your ceiling.

Gate upgraded participation conditions on many projects so that your staking cap depends on your recent trading activity. The calculation:

**60-day total volume = 60-day spot volume + (60-day futures volume × 40%)**

Higher volume unlocks a higher staking limit. At the moment an hourly payout lands, your 60-day volume also has to clear that round's minimum requirement. If it doesn't, you lose that hour's airdrop rather than the whole position.

Missing the volume threshold has no effect on redemption. You can withdraw staked assets whenever you like, and anything you leave staked is returned to your spot account when the campaign ends. The rules are set per round, so check the specific announcement instead of assuming last month's numbers.

One related detail: assets staked in Launchpool still count toward HODLer Airdrop eligibility, Launchpad, and VIP tier holding calculations. Parking coins in a pool doesn't cost you status elsewhere.

## How to join a round

The flow is short enough to list:

1. Create a Gate account and complete identity verification. It's mandatory for participation.
2. On web, go to **Finance → Launchpool**. In the app, the path is **Home → Finance → Launch → Launchpool**.
3. Open the round you want and read the pool card: reward token, accepted stake assets, per-user cap, any volume requirement, campaign start and end time.
4. Hit **Participate**, enter the amount, confirm.
5. Track accumulated rewards under **Airdrop Records**. Payouts land in your spot account hourly.
6. If you want the extra yield boost, tick the option that routes redeemed funds into fixed-term Simple Earn when you stake, and pick your term.

Step 6 deserves its own section, because it's the difference between earning one stream and two.

👉 [Set up an account and open the current Launchpool round](https://bit.ly/GateVIP)

## The Simple Earn upgrade: where an extra few percent comes from

In August 2025, Gate rolled out a combined "Launchpool + fixed-term Simple Earn" programme. If you stake BTC, ETH, GT or USDT in Launchpool and choose to auto-transfer your redeemed funds into fixed-term Simple Earn, you get Simple Earn yields of up to 4% APR on top of the airdrop rewards, plus a bonus boost on the airdrop itself.

The announcement used a clean illustration: if you were earning 10 tokens per hour, the boost takes that to 19 per hour. That's a 90% uplift on the reward stream, not on your principal.

Things worth knowing before you tick that box:

- The default destination is a 7-day fixed-term Simple Earn product. Funds transferred there are locked until maturity and can't be redeemed early. Plan liquidity accordingly.
- Flexi Simple Earn is excluded from the boost.
- If the fixed-term product you picked is already at its subscription cap, the platform subscribes you into the flexi equivalent instead, and you still qualify for the bonus.
- Only fixed-term holdings that arrived via Launchpool redemption qualify. Buying the same product directly on your own doesn't count.
- Once you opt in on one pool, every later redemption from that pool auto-transfers. It's a per-pool setting, so it isn't a one-off toggle you can casually reverse.

## What the APR numbers actually mean

Launchpool pages show an estimated APR, recalculated hourly. It is not a fixed rate and it is not a promise. Two variables drive it: the reward release rate and the total value staked in that pool. More capital arriving in the same pool dilutes everyone's share, which pushes the displayed APR down. When capital leaves, it climbs.

Here's what recent rounds looked like at the time they were reported, so you can see the spread:

| Round | Reward pool | Pool snapshot |
| --- | --- | --- |
| MarsCat (MCAT), reported 11 Sept 2026 | 2,000,000 MCAT | USDT pool ~$83.7M staked, est. 13.69% · GT pool 174.53% · MCAT pool 7,522.57% |
| SNDKG, reported 10 Aug 2026 | Not stated in report | ETH pool 25,677 ETH at 3.45% · BTC pool 1,443 BTC at 1.23% · GT pool 1,174,131 GT at 4.13% |
| SPCX, running alongside on 10 Aug 2026 | Not stated in report | GUSD pool over 80M GUSD at 4.41%, roughly 8.21% combined with GUSD flexi · USDT pool ~$92M at 5.59% |
| Interfold (FOLD) | 2,029,221 FOLD | ETH 3.61% · BTC 2.49% · FOLD pool 590.76% |
| Hunter Biden's Laptop (LAPTOP) | 1,289,608 LAPTOP | LAPTOP pool 263.05% · BTC pool 2.39% |
| Tether Gold (XAUT) | 34 XAUT | USDT 3.35% · XAUT 12.45% · GT 6.38% |
| CP | Not stated in report | ETH pool 15,974 ETH at 3.15% · BTC pool 1.41% · CP pool 61.65% |
| ALIGN | Not stated in report | USDT pool ~$137.2M at 4.76% · GT pool 0.96% · ALIGN pool 116.85% |

Read that table again with one pattern in mind: nearly every eye-catching number sits in the project's own token pool. Staking FOLD to earn FOLD, or LAPTOP to earn LAPTOP, produces triple-digit APRs because both sides of the arrangement are the same volatile asset. When the pool is BTC, ETH, USDT or GT, the rate lands somewhere between roughly 1% and 13%.

That distinction matters more than the headline. A 7,522% APR paid in a brand-new token isn't 7,522% in dollars. It's a quantity of tokens whose price is decided by a market that opened days ago. Two things can both be true: the token count you receive can be large, and the dollar value can be disappointing once you try to sell into thin liquidity. The number on the page is a snapshot of one hour, taken at one pool size, and it will look different by the time you finish reading.

## Fees, VIP tiers, and how the volume rule and your fee rate connect

Since the 60-day volume rule governs your staking cap, and the same kind of volume data governs your fee tier, it's worth looking at both together. Gate's current fee schedule runs from VIP 0 to VIP 16, with three upgrade paths: 30-day trading volume, 14-day average GT holdings, or account asset value. Meeting any one of them is enough.

| VIP level | 30-day trading volume (USD) | Spot maker / taker | Get started |
| --- | --- | --- | --- |
| VIP 0 | 0 | 0.10% / 0.10% | [Open a VIP 0 account](https://bit.ly/GateVIP) |
| VIP 1 | 60,000 | 0.099% / 0.099% | [Start earning toward VIP 1](https://bit.ly/GateVIP) |
| VIP 2 | 120,000 | 0.098% / 0.098% | [Reach the VIP 2 threshold](https://bit.ly/GateVIP) |
| VIP 3 | 240,000 | 0.097% / 0.097% | [Move up to VIP 3](https://bit.ly/GateVIP) |
| VIP 4 | 500,000 | 0.095% / 0.096% | [Check the VIP 4 requirements](https://bit.ly/GateVIP) |
| VIP 5 | 1,000,000 | 0.09% / 0.095% | [See what VIP 5 unlocks](https://bit.ly/GateVIP) |
| VIP 6 | 3,000,000 | 0.085% / 0.09% | [Compare a VIP 6 rate](https://bit.ly/GateVIP) |
| VIP 7 | 8,000,000 | 0.08% / 0.085% | [Review VIP 7 conditions](https://bit.ly/GateVIP) |
| VIP 8 | 20,000,000 | 0.075% / 0.08% | [Look at the VIP 8 tier](https://bit.ly/GateVIP) |
| VIP 9 | 50,000,000 | 0.07% / 0.075% | [Open VIP 9 details](https://bit.ly/GateVIP) |
| VIP 10 | 100,000,000 | 0% / 0.058% | [Check VIP 10 pricing](https://bit.ly/GateVIP) |
| VIP 11 | 120,000,000 | 0% / 0.045% | [See VIP 11 terms](https://bit.ly/GateVIP) |
| VIP 12 | 240,000,000 | 0% / 0.037% | [Review VIP 12 access](https://bit.ly/GateVIP) |
| VIP 13 | 440,000,000 | 0% / 0.03% | [Check VIP 13 criteria](https://bit.ly/GateVIP) |
| VIP 14 | 800,000,000 | 0% / 0.025% | [Open VIP 14 information](https://bit.ly/GateVIP) |
| VIP 15 | 1,600,000,000 | 0% / 0.022% | [See VIP 15 requirements](https://bit.ly/GateVIP) |
| VIP 16 | 3,000,000,000 | 0% / 0.02% | [View top-tier fee details](https://bit.ly/GateVIP) |

A few notes that matter more than the rows themselves:

- **Pay in GT and the rate drops again.** VIP 0 goes from 0.10%/0.10% to 0.09%/0.09% when fees are settled in GT. At VIP 5 the gap is 0.09%/0.095% versus 0.081%/0.085%, and at VIP 8 it's 0.075%/0.08% versus 0.06%/0.072%. The discount gets more useful the higher you climb.
- **VIP 15 and VIP 16 are different animals.** Gate states these aren't reachable through the normal VIP upgrade path. They're for senior institutional users, and accounts where API trading volume accounts for 60% or more of activity are upgraded automatically. Regular VIP users can't step into them.
- **The alternative paths are cheaper than they look for some users.** The GT holdings route starts at 50 GT for VIP 1, and the asset-value route starts at $2,000 for VIP 1 and reaches $100,000,000 at VIP 16. If you'd rather hold GT than churn volume, that route exists, and it feeds directly into the 14-day average holdings snapshot used for tier calculations.
- **One caveat on spot rates for newcomers.** Third-party fee explainers are still circulating pre-April 2026 figures, including a 0.20% starting spot rate. Gate's own fee page currently shows 0.10%/0.10% at VIP 0, which is the figure to plan around, but confirm on the live page before you size a strategy around it.
- **Futures sit on a separate schedule.** At VIP 0 the futures rate is 0.020% maker / 0.050% taker, tightening to 0.016% taker at the top tier. Fees are charged on executed quantity only, never on unfilled orders.

## Launchpool vs CandyDrop vs HODLer Airdrop

Gate groups these three products under the same "Launch" menu, which is why people mix them up. They're different mechanisms.

|  | Launchpool | CandyDrop | HODLer Airdrop |
| --- | --- | --- | --- |
| Core action | Stake assets into an active pool | Complete tasks (trading, deposits, referrals, depending on project) | Hold GT according to the round's rules |
| Reward form | New project tokens, paid hourly from the round's pool | Airdrop pool share or fixed rewards | Airdrop distributed based on GT holdings |
| Entry control | Follow each pool's stake/subscribe flow | Must click Join Now on the project page | Follow each round's rules |
| Account notes | Round-specific eligibility requirements | Main account only | Round-specific rules |

If you already hold BTC, ETH, GT or USDT, Launchpool is the one that turns idle balance into a second income stream. CandyDrop is work, not staking. HODLer Airdrop is a GT-holding benefit, full stop.

👉 [Compare all three Gate Launch products in one account](https://bit.ly/GateVIP)

## Unstaking, caps, and the details people miss

Redemption is flexible. You can pull your stake at any time, and you can add to it at any time.

Two consequences follow. First, pulling out early can cost you that hour's rewards because the snapshot average drops. Second, when you redeem, or when the campaign ends, staked funds default to being transferred into Simple Earn unless you untick the box. If the redeemed amount is below Simple Earn's minimum subscription, or Simple Earn doesn't support that asset, the funds go back to spot instead.

Then there are the caps. Per-user hourly reward ceilings are set per project. Larger staking limits are gated by your 60-day volume. If you're planning to move serious size into a pool, check both before you commit, because the cap is the real limit on what the APR can deliver for you.

One more: if a project ends early, your principal is automatically redeemed at that moment. The final payout happens at the top of the hour following the end, and payouts before that stay intact.

## Quick answers to the questions that come up most

**Can I join several Launchpool rounds at once?** Yes. One campaign, valid for one project. You can be in pool A and pool B for different projects at the same time. Each pool is staked separately, so being in pool A earns you nothing from pool B.

**Does staking hurt my VIP tier?** No. Staked assets still count for HODLer Airdrop, Launchpad and VIP holding calculations.

**Is the APR guaranteed?** No, and the page doesn't claim it is. APR is an hourly estimate that moves with pool size, participation and the market price of both tokens involved. Tokens released hourly can also fall in price before you sell them.

**Do I need verification?** Yes, identity verification is required to take part.

## So is it worth doing?

If you already hold USDT, BTC, ETH or GT and they're sitting still, Launchpool is one of the more straightforward ways to put them to work without changing your portfolio. The staking is flexible, the rewards land hourly, and nothing about your existing position is sold to participate.

The judgment that actually matters is which pool you pick. The pools built on BTC, ETH, USDT or GT produce modest but real numbers, in the low single digits up to low teens in the snapshots above, and they're paid in assets you can price immediately. The pools that spike into the hundreds or thousands of percent pay you in the project's own new token, and that token is exactly as volatile as a brand-new listing tends to be. A big token count and a big dollar return are not the same thing.

So pick your pool based on which reward asset you'd be willing to hold, then check the staking cap your 60-day volume gives you. If the cap is small, the APR is mostly decorative.

👉 [Sign up on Gate and check the caps and APR on the current round](https://bit.ly/GateVIP)
