# The offer: yerby

Method: the Offers lens (`founder-board/lenses.md`, a summary of a published framework). Inputs: `panel/results.md` (100 simulated buyers), `competitors.md`, `numbers.json` / `cfo.md`, `pricing.md`, `board.md`. All amounts are in CZK. **ESTIMATE** marks numbers that are not quotes.

Your decisions in this run: **no money-back guarantee**, and **sugar is no more than 4 g per can**. Print the exact figure from your nutrition declaration.

## The headline result

**The First Run 12 offer (v2) did worse than the plain can: 3 of 20 bought (15%), against 28 of 100 (28%) for v1.** The cause is clear in the answers. Leading with a **649 CZK 12-pack** asks people to commit to 12 cans of a drink they have never tasted, and they refuse:

> *"I'm not paying 649 for twelve of something that might taste like grass tea before I've had one."* (P005, bought a single can instead)
> *"I'd rather grab one can at a café with the voucher first, but I don't have the voucher without buying the pack."* (P001)

The sugar figure helped: label readers mentioned "4 g" approvingly, and the sugar objection disappeared for most of them. The numbered First Run did nothing for anyone except trend chasers. **What's wrong is the order of the offer, not the product: buyers want to taste first and commit second.** The recommended offer (v3, below) puts that order first. v3 is **not yet re-tested**.

Caveat on the comparison: `--quick` with the same seed deals 20 different cards from the first 20 of the 100. Weighting the v1 buy rates by this panel's mix of buying behaviours, v1 would be expected to score **about 30%** with these 20 people (ESTIMATE). So the drop to 15% is real, not a sampling artefact, although at n=20 it is a direction, not a precise number.

## 1. The problem list (in the buyer's words, from the panel and competitor complaints)

**Before buying**
1. "Unsweetened yerba mate sounds bitter, like grass tea."
2. "I won't pay for 12 of something I've never tasted."
3. "55 CZK is more than a Red Bull for less drink."
4. "80 mg is less than my usual can. Will I feel it?"
5. "Fruit concentrate means sugar. How many grams?"
6. "Every brand says natural now; YEAHRBA is cheaper on Rohlík."
7. "The label is in English. Is this even Czech? Who makes it?"
8. "I buy multipacks on offer; single cans online is the opposite of how I shop."
9. "Why pay for a can when coffee, matcha or water does the job?"

**Buying it**

10. "It's not where I shop: petrol station, Albert, Tesco, Rohlík, GymBeam."
11. "I'm not ordering cans from yet another e-shop."
12. "'Selected cafés' tells me nothing about whether I'll ever see one."
13. "Delivery on top makes the can even pricier."
14. "Cafés are closed when I work night shifts."

**After buying**

15. "If the first can is bitter, I'm stuck with 11 more."
16. "It's a one-off try, not a switch from my usual."
17. "The novelty wears off."
18. "Will it be the same every time I buy it?" (shelf life and consistency)

## 2. Solutions, scored (value to buyer 1–5, cost to deliver 1–5, from the CFO lines)

| # | Solution | Answers | Value | Cost | Keep? |
| --- | --- | --- | ---: | ---: | --- |
| A | **Free tasting cans** at cafés, gyms, pop-ups and launch events (cold, opened on the spot) | 1, 2, 4, 15 | 5 | 2 (inside the 5 CZK/can marketing line) | **Yes, core of v3** |
| B | **Single cans at 59 in fridges people already pass**: partner cafés, bistros, gyms, bike shops; the list published by street, not "selected cafés" | 10, 12, 14, 16 | 5 | 2 | **Yes** |
| C | **Sugar and caffeine on the front**: "80 mg caffeine · ≤4 g sugar · 4 ingredients" | 4, 5, 6 | 5 | 1 | **Yes (done in v2; it worked)** |
| D | **"Taste first, then the 12-pack"**: a code under the tab of every single and sample can gives 50 CZK off a first 12-pack | 2, 8, 15 | 4 | 2 (50 CZK per redeemed pack ≈ 4.20/can; ESTIMATE 30% redemption) | **Yes** |
| E | **12-pack 649 delivered to a pickup point for 39** (yerby covers ~36) | 8, 13 | 3 | 2 | Yes, as step 2, not step 1 |
| F | **Monthly 12-pack subscription 609, skip or cancel anytime** | 16, 17 | 3 | 1 | Yes, step 3 |
| G | **Czech-language panel and "a Czech company from …"** with producer details | 7 | 3 | 1 | Yes (likely legally required anyway, see notes) |
| H | Numbered First Run cans | 17 | 2 (trend chasers only) | 1 | Keep as true scarcity, but don't lead with it |
| I | Free-can voucher inside the 12-pack | 12 | 1 (people wanted it before buying) | 2 | **Drop.** Move the value to D |
| J | Money-back guarantee | 15 | 4 | 3 (2.70/can at 5% claims) | **Dropped (your call)**. A partly substitutes |
| K | Listing on Rohlík / GymBeam / Vilgain | 10, 11 | 5 | ? (retail margins unknown) | Pursue next, but don't promise it in the offer until it's signed |
| L | A stronger 150 mg version | 4 | 3 (gym only) | 5 (new SKU) | No. Gym buyers aren't the target |

## 3. The stack (v3, recommended): **"Taste it first"**

- **Core:** a cold can that tastes like lemon and grapefruit mate, not grass, with 80 mg of natural caffeine, no more than 4 g of sugar and four ingredients. It's sold where you already stop.
- **Bonus 1 (kills "never tasted it"):** **free tasting cans** at launch events and partner cafés during launch month.
- **Bonus 2 (kills "where do I buy it"):** **single cans at 59** in named partner cafés, bistros and gyms, with a list on the website by street.
- **Bonus 3 (kills "12 is a gamble"):** **"Liked it? 50 CZK off your first 12-pack"**, with a code under the tab of every single and sample can.
- **Step 2:** the **First Run 12** (649, pickup point 39), the first 3,000 cans, numbered, **until 31 January 2027 or sold out**. Both limits are true.
- **Step 3:** a **subscription** at 609 a month, skip or cancel anytime.
- **Guarantee:** none, by your choice. Online sales still carry the statutory 14-day withdrawal right for unopened goods in the EU (check with a lawyer). Free tasting does most of a guarantee's work at a lower cost.
- **Name:** **"Taste it first"** for the launch campaign, with the **First Run 12** as the pack.

**Cost check (CFO tool, `numbers-offer.json`, `cfo-offer.md`).** On the base ramp, a 12-pack at 649 with 39 CZK pickup delivery (yerby covers ~36), a 12-can box, 2.5% fees and 5 CZK/can marketing comes to a **contribution of 17.55 a can**. Break-even is 19 cans a day, and year 1 operating profit is +41,459. That's the same as the CFO base (17.62), because the higher pack price pays for the pickup subsidy. (The voucher line in that file is dropped in v3; add back about −4.20/can × 30% redemption ≈ −1.30 for bonus 3, ESTIMATE.) The guarantee is not in the costs.

The free tasting cans are covered by the 5 CZK/can marketing line: ~1,800 free cans over year 1 at 24 CZK (ESTIMATE, about 20% of the 9,200 cans sold). Count them against that budget.

## 4. The value equation (1–10)

| element | v1 plain can | v2 First Run 12 | v3 Taste it first (proposed) | what moves it |
| --- | ---: | ---: | ---: | --- |
| Dream outcome (clean caffeine you enjoy) | 6 | 6 | 6 | The product stays the same |
| Perceived likelihood (it tastes good and works) | 3 | 4 | **7** | Sugar/caffeine on the front (+1); **tasting it free** (+3) |
| Time to result | 7 | 5 | **8** | v2 adds delivery wait; v3 gives a cold can now |
| Effort and sacrifice | 4 | 3 | **7** | v2 asks for a 12-can commitment and a trip to a pickup point; v3 is one free or 59 CZK can in a place you're already in |

## 5. The re-test

| | pitch | buyers | buy rate |
| --- | --- | ---: | ---: |
| v1 | plain can, 55, e-shop + cafés | 100 | **28%** |
| v2 | First Run 12 pack-first + sugar figure | 20 (same seed, `--quick`) | **15%** (v1 weighted to the same mix: ~30%, ESTIMATE) |
| v3 | Taste it first | not yet run | — |

- **Objections that dropped in v2:** sugar ("4 g" now reads as a plus to label readers); "is it natural" was mostly gone.
- **Objections that grew:** "12 cans I've never tasted" (top objection in v2, in most no's); delivery plus pickup point.
- **Unchanged:** "not where I shop" (petrol stations, supermarkets, Rohlík, GymBeam), "80 mg is weaker", English label and "is it Czech".
- **Of the 3 who bought, 2 bought single cans at the café and only 1 bought the 12-pack.**

`pitch.md` now holds v3. v1 and v2 are kept as `pitch-v1.md` and `pitch-v2.md`. Run another `--quick` panel to test v3 before printing anything.

## Notes to check before launch (not legal advice)

- **The caffeine warning is probably mandatory.** 80 mg in 330 ml is about 242 mg/l, above the EU 150 mg/l threshold (Regulation 1169/2011). The label must then say "High caffeine content. Not recommended for children or pregnant or breast-feeding women", with the mg per 100 ml, in Czech. Check the current can design. → `/founder-ops`
- **Czech-language labelling** of mandatory information is required for sale in Czechia. The panel also kept asking "is it Czech?"
- **No health claims.** Avoid "energy boost", "focus" or "no crash" wording for caffeine. The EU has no authorised caffeine health claims. Factual content statements ("80 mg caffeine") are fine.
- **"No more than 4 g of sugar"** must match the nutrition declaration. Don't say "no added sugar" when fruit concentrate is in the drink, without checking.
