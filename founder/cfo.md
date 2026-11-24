# The numbers: yerby

All amounts in CZK. yerby s.r.o. is a non-VAT payer, so the 55 CZK price is the full consumer price with no VAT on top, and VAT on costs cannot be reclaimed (it is inside the 24 CZK COGS). **ESTIMATE** marks every number that is not a founder quote; sources are in `cfo-sources.md`. This is not financial, tax or legal advice: have an accountant check the structure, VAT and costs before money moves.

## CFO's note

**The margin.** At 55 CZK a can earns **31.00 CZK (56%) before fulfilment and marketing**, but **17.60 CZK (32%) after them** (estimated: carton 3, payment fees 1.40, shipping subsidy 4, marketing/sampling 5). At the base plan (1,000 cans/month from month 8) the profit margin is **14%**. Year 1 makes **+41,919 CZK** operating profit but ends **−258,081 CZK** after the 300,000 startup. The startup is **not earned back in year 1**.

**The line to watch: price, and the estimated per-can costs around it.** The contribution is thin enough that a 10% price cut, or 15% higher unit costs, turns year 1 into a loss (−8,681 / −9,693 CZK). The five estimated cost lines (13.40 CZK together) matter as much as the production quote, so get real quotes for carton, shipping and payment fees first.

**Volumes you asked for** (exact, from contribution = 17.62 CZK at 55, 31.27 at 69, 41.02 at 79):

| price | break-even (covers 10,000/month) | pays back 300,000 within 12 months (flat volume) | same, if the 300,000 already includes the 72,000 batch |
| ---: | ---: | ---: | ---: |
| 55 | **568 cans/month** (19/day) | **1,987 cans/month** (66/day) | 1,646 cans/month |
| 69 | 320 cans/month | 1,120 cans/month | 928 cans/month |
| 79 | 244 cans/month | 854 cans/month | 707 cans/month |

Before fulfilment and marketing (COGS only), break-even would be 323 / 223 / 182 cans a month. That is the gap between the 56% headline margin and the real one.

**Cash.** The tool counts the 24 CZK COGS when a can sells, and gives a cash need of **308,880 CZK**. In reality, the 72,000 batch is paid before anything sells. That puts peak cash out at about **372,000–381,000 CZK** (ESTIMATE: 300,000 startup + 72,000 batch + early-month losses). At 1,000 cans a month, a new batch of 3,000 is needed about every 3 months.

**Open question for you.** Is the 72,000 batch inside the 300,000, or on top of it? The model treats the 300,000 as excluding the batch, because the batch is already counted can by can in COGS. If the batch is included, the non-inventory startup is 228,000. The base ramp then ends year 1 at −185,897 instead of −258,081. That's better, but still not paid back.

### Scenarios: flat volume all year, 300,000 startup

| price | cans/month | contribution/can | margin at plan | year 1 operating profit | startup paid back |
| ---: | ---: | ---: | ---: | ---: | --- |
| 55 | 500 | 17.62 | −4% | −14,280 | no |
| 55 | 1,000 | 17.62 | 14% | 91,440 | no |
| 55 | 1,500 | 17.62 | 20% | 197,160 | no |
| 69 | 500 | 31.27 | 16% | 67,620 | no |
| 69 | 1,000 | 31.27 | 31% | 255,240 | no |
| 69 | 1,500 | 31.27 | 36% | 442,860 | month 9 |
| 79 | 500 | 41.02 | 27% | 126,120 | no |
| 79 | 1,000 | 41.02 | 39% | 372,240 | month 10 |
| 79 | 1,500 | 41.02 | 43% | 618,360 | month 6 |

The payment fee is scaled to 2.5% of each price.

On the base ramp (300 → 1,000 cans/month, 9,200 cans in year 1), year 1 after the 300,000 startup comes out at **55: −257,897 · 69: −132,318 · 79: −42,618**. With a 228,000 startup, 79 CZK pays back in month 12.

**Caution on 69 and 79: this table assumes the same volume at a higher price, and the panel says that won't happen.** Median simulated buyer answers were: a bargain at 35 CZK, getting expensive at 50, too expensive at 65. 18 of 100 buyers already wouldn't buy at 55 or below. At 69–79 you'd be selling to the label-reader and trend-chaser niche, and volume would likely fall. `/founder-pricing` should set the price, not this table.

### Three ways to improve the margin (base ramp, 55 CZK)

1. **Price 69 CZK** (with a multipack or offer that justifies it). Contribution rises from 17.62 to 31.27, break-even falls from 568 to 320 cans a month, and year 1 operating profit goes from 42,103 to 167,682. This only works if volume holds (see the caution above).
2. **Stop subsidising D2C shipping** (customer pays, or a minimum order that covers it). That's +4.00 CZK a can: contribution 21.60, break-even 463 cans a month, about +36,800 CZK over year 1 (9,200 cans × 4).
3. **Cut production cost by 3 CZK a can** through a larger run or a renegotiated quote. That's +27,600 CZK over year 1 and break-even 486 cans a month. You need a real quote from the producer.

**Channel warning (ESTIMATE).** A café buying at a wholesale price of 35 CZK leaves about 9.50 CZK a can (COGS 24 + carton and delivery ~1.50), with break-even at 1,053 cans a month. At 40 CZK wholesale it leaves 14.50, with break-even at 690 cans a month. Cafés are good for sampling and the brand, but at those prices they won't pay back the startup on their own. Distributor and chain margins are unknown and would leave less.

**VAT (check with an accountant).** Base year 1 revenue is about 506,000 CZK, well under the Czech VAT registration threshold (2,000,000 CZK turnover in 12 months, as of the 2025 rules). If you cross it, you either have to add VAT to the shelf price or absorb it, which would cut contribution by about 9.5 CZK a can at 55 CZK.

### The board's money conditions
- [~] **Positive margin per can in each channel:** D2C is positive at the estimates (17.60). Cafés are thin (about 9.50 at a 35 wholesale price). Distributors and chains are not modelled, because there are no terms yet. **Partly met.**
- [ ] **Pays back the startup:** not in year 1 at 55 CZK, at any of the modelled volumes up to 1,500 a month. **Not met.**
- [ ] **Real per-can costs instead of estimates:** 13.40 CZK of the 37.40 is still estimated. **Not met.**

---

# Unit economics: yerby (yerby s.r.o., Czechia, non-VAT payer). All amounts in CZK

Every number below comes from the input file. Nothing is looked up or guessed.

## One can

| line | per can |
| --- | ---: |
| Price | 55.00 CZK |
| Production COGS, 330 ml can (founder quote, incl. non-reclaimable VAT) | -24.00 CZK |
| ESTIMATE: shipping carton / packaging (~18 CZK per 6-pack box) | -3.00 CZK |
| ESTIMATE: payment gateway fees (~2.5% of price incl. per-order fee) | -1.40 CZK |
| ESTIMATE: D2C shipping subsidy (~50 CZK per 12-can order) | -4.00 CZK |
| ESTIMATE: marketing / CAC incl. free sampling cans | -5.00 CZK |
| **Contribution** (what each can leaves to pay the fixed costs) | **17.60 CZK** (32%) |

## The margin that matters

Fixed costs: 10,000 CZK a month (Monthly operating costs (founder estimate) 10,000 CZK).

- **Break-even: 19 cans a day.** Below that you lose money every month.
- **Profit margin at your plan** (33 a day): **14%** of every sale, after every cost.

## Year 1, month by month

| month | cans a day | revenue | profit | cumulative (after 300,000 CZK startup) |
| ---: | ---: | ---: | ---: | ---: |
| 1 | 10 | 16,500 CZK | -4,720 CZK | -304,720 CZK |
| 2 | 13 | 21,999 CZK | -2,960 CZK | -307,680 CZK |
| 3 | 17 | 27,501 CZK | -1,200 CZK | -308,880 CZK |
| 4 | 20 | 33,000 CZK | 560 CZK | -308,320 CZK |
| 5 | 23 | 38,499 CZK | 2,320 CZK | -306,000 CZK |
| 6 | 27 | 44,001 CZK | 4,080 CZK | -301,920 CZK |
| 7 | 30 | 49,500 CZK | 5,840 CZK | -296,080 CZK |
| 8 | 33 | 54,999 CZK | 7,600 CZK | -288,480 CZK |
| 9 | 33 | 54,999 CZK | 7,600 CZK | -280,880 CZK |
| 10 | 33 | 54,999 CZK | 7,600 CZK | -273,281 CZK |
| 11 | 33 | 54,999 CZK | 7,600 CZK | -265,681 CZK |
| 12 | 33 | 54,999 CZK | 7,600 CZK | -258,081 CZK |

- **Year 1 operating profit: 41,919 CZK** on 505,997 CZK of revenue.
- After the 300,000 CZK startup spend: -258,081 CZK.
- Startup money earned back: not within year 1.
- Cash you need before it pays for itself: **308,880 CZK**.

## What if

| scenario | margin at plan | break-even a day | year 1 profit |
| --- | ---: | ---: | ---: |
| Base plan | 14% | 19 | 41,919 CZK |
| Price -10% | 4% | 28 | -8,681 CZK |
| Volume -20% | 9% | 19 | 9,535 CZK |
| Unit costs +15% | 4% | 28 | -9,693 CZK |

## Red flags

- The startup spend is not earned back within year 1.
