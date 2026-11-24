# Competitors: yerby

Researched 24 Nov 2026. Prices come from live Rohlik.cz listings (prices, ingredients and caffeine as printed). Rohlik is the largest Czech online grocer and stocks every relevant brand, so it gives one consistent shelf to compare on. Many prices were promotional on the day, so regular prices are noted where shown. Raw rows are in `competitors.csv`.

**What could not be reached:** review pages on heureka.sk, slevomat.cz, zbozi.cz and the review sections on rohlik.cz were blocked from this research session, and search turned up no independent reviews. **The complaints section below is therefore thin.** See "What to do about the gap in this research" at the end.

## 1. The table, most direct first

| # | Name | Type | Pack | Price | What's in it | Their line |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | **[YEAHRBA Mate energy](https://www.rohlik.cz/1482152-yeahrba-mate-energy-original-perliva-plech)** (CZ, Brno) | direct | 330 ml **can** | **39.90** (sale to 31 Dec; an earlier snapshot showed [59.90](https://www.rohlik.cz/1482151-yeahrba-mate-energy-minty-pineapple-sparkling)) | Mate concentrate + **sugar 4.9 g/100 ml**, guarana, maca, ginkgo, magnesium, B6; 3 flavours | "Přírodní zdroj energie bez chemie a výčitek" |
| 2 | [Club-Mate](https://www.rohlik.cz/1294697-club-mate) (DE) | direct | 330 ml glass + 3 CZK deposit | 36.90 (regular 56.90) | Glucose-fructose syrup, sugar, mate extract 0.4%, **added caffeine**, 20 mg caffeine/100 ml | "povzbuzuje výrazněji než káva nebo čaj" (retailer copy) |
| 3 | [Erebos](https://www.rohlik.cz/1384302-erebos-original-sklo) (CZ, Frýdek-Místek) | direct | 250 ml glass | 54.90 (regular 63.90) | Mate, kola, guarana, rhodiola + cane sugar; no preservatives, colours or artificial flavours | "zdravější alternativa energy drinku" |
| 4 | [Voelkel BioZisch BIO Mate](https://www.rohlik.cz/1445437) (DE) | direct | 330 ml glass | 46.90 | Organic mate, agave, 30 mg caffeine/100 ml | "silnou dávkou kofeinu v BIO kvalitě" |
| 5 | [CANS+ Performance](https://www.rohlik.cz/1480796) (CZ brand, Praha) | indirect | 330 ml **can** | 40.90 | **No sugar, no sweeteners.** Caffeine from coffee 12.8 mg/100 ml, L-theanine, B6/B12, magnesium | "Bez cukru. Bez sladidel. Feels Better." |
| 6 | [Koka Mate BIO](https://www.rohlik.cz/1439223-koka-mate-bio-ledovy-caj-sklo) (DE) | indirect | 330 ml glass | 47.90 | Coca leaf, black tea, mate | "Neobsahuje žádné umělé látky." |
| 7 | [Bacilli BIO Kombucha maté](https://www.rohlik.cz/1456706) | indirect | 330 ml | 52.90 | Kombucha on mate, apple, lemon | – |
| 8 | [Seicha Matcha](https://www.rohlik.cz/1442995) | indirect (the brand's chosen "enemy") | 330 ml glass | 46.90 | Matcha 0.4%, cane sugar, lime, chlorophyll colour | – |
| 9 | [Red Bull](https://www.rohlik.cz/1287301) | indirect | 250 ml can | 44.90 single; 4-pack 179.90 | Classic or zero sugar | – |
| 10 | [Monster](https://www.rohlik.cz/en-CZ/1295189-monster-energy-carbonated-energy-drink) | indirect | 500 ml can | 45.90; 4-pack 144.90 | Ultra range: sucralose, acesulfame K, preservatives, E102/E110 | – |
| 11 | [Big Shock!](https://www.rohlik.cz/1290277) (CZ) | indirect | 500 ml can | 34.90 (regular 45.90) | Energy drink incl. "Smart Energy" line | – |
| 12 | [Semtex](https://www.rohlik.cz/1297121) (CZ) | indirect | 500 ml can | 19.90 (regular 35.90) | Sugar, glucose-fructose syrup, taurine, caffeine, caramel colour | – |
| 13 | [Hacker Energy](https://www.rohlik.cz/1458885) | indirect | 500 ml can | 25.90 | Sugar + sucralose, 32 mg caffeine/100 ml | – |
| – | Loose yerba brewed at home ([Alza](https://www.alza.cz/maxi/sypane-caje-mate/18905739.htm)) | substitute | 0.5–1 kg | ~240–260 CZK/kg (search snapshot, not opened) | Playadito, Rosamonte, Canarias, Taragui | – |
| – | Coffee | substitute | – | – | The default caffeine fix for the same buyer | – |

Two things a buyer can't compare yet: **yerby's caffeine per can** and **its sugar per 100 ml** (from the citrus concentrates). Every mate competitor prints caffeine. Club-Mate, Voelkel, Hacker and CANS+ all state mg per 100 ml.

## 2. Price range

Prices are normalised to a 330 ml serving, the size of a yerby can.

| Group | Lowest | Median | Highest |
| --- | --- | --- | --- |
| Mate, natural and functional drinks (rows 1–8) | 36.90 (Club-Mate, sale) | **46.90** | 72.50 (Erebos per 330 ml; 84 at regular price) |
| Mainstream energy, per 330 ml equivalent | 13.10 (Semtex, sale) | 23.00 (Big Shock) | 59.30 (Red Bull 250 ml) |
| Closest twin: YEAHRBA, Czech mate energy can | 39.90 (sale) | – | 59.90 (earlier snapshot) |

**At 55 CZK, yerby would be the most expensive 330 ml can of its kind on this shelf.** That's 15 CZK (38%) above YEAHRBA's current price and 8 CZK above the median natural drink. Only Erebos (by volume) and a single Red Bull are pricier per serving. A mainstream energy-drink buyer pays 13–30 CZK per 330 ml for Monster, Big Shock or Semtex, so 55 CZK is 2–4× their usual spend. The 79 CZK end of the test range has no precedent on this shelf. `/founder-pricing` should test against these anchors.

## 3. Positioning map

The two axes that matter to this buyer are the price per 330 ml (x) and how clean the label is (y).

```
 CLEAN  ^
 (no sugar,       CANS+ (40.90, coffee caffeine)        ·  yerby? (55, if truly no added sugar)
  no sweetener,
  no synthetics)
        |                                Voelkel BIO Mate (46.90, agave)   Koka Mate (47.90)
        |                                Bacilli kombucha maté (52.90)
        |   YEAHRBA (39.90, sugar + guarana/maca)          Seicha Matcha (46.90, cane sugar)
        |                                                           Erebos (72.50/330, cane sugar)
        |   Club-Mate (36.90, syrup + added caffeine)
        |
        |  Semtex (13)  Hacker (17)  Big Shock (23)  Monster (30)          Red Bull (59)
 SYNTH- |
 ETIC   +--------------------------------------------------------------------------------> PRICE / 330 ml
        cheap                                                                    expensive
```

The bottom of the map is crowded and cheap. The middle is a cluster of "natural with sugar" mate and herbal drinks at 37–55 CZK, almost all in glass. Only CANS+ sits at the top, and its caffeine comes from coffee, at a low dose (~42 mg per can).

## 4. What their customers say

**Thin.** No review pages could be read, and search turned up almost no Czech consumer reviews of mate drinks. The few signals:

- **YEAHRBA ratings are sparse.** Search summaries mention one 100% rating on [Heureka.sk](https://www.heureka.sk/znacky/yeahrba/), and mixed ratings (5/5 and 1.7/5) on [Slevomat](https://www.slevomat.cz/podnik/176740-yeahrba-drinky). I couldn't open either page to verify. *Thin (<3 reviews).*
- **Mate is an acquired taste.** A trade commentary in [Brauwelt](https://brauwelt.com/en/international-report/europe-russia/624513-adieu-bionade-whats-the-next-big-thing-comment) reads Club-Mate's own tagline ("you'll get used to it") as an admission that the taste puts people off at first. This is press, not reviews. *Thin.* It does support the board's first-sip risk.
- **Popularity signals, not complaints:** the Rohlik listings show "in favourites" counts of ~2,400 for [Club-Mate](https://www.rohlik.cz/en-CZ/1294697-club-mate), ~3,000 for [YEAHRBA Maracuja](https://www.rohlik.cz/1482153-yeahrba-mate-energy-sparkling-passion-fruit-330-ml), ~600 for [Erebos](https://www.rohlik.cz/en-CZ/1384302-) and ~3,050 for [Red Bull Zero](https://www.rohlik.cz/1372055-red-bull-zero-plech). YEAHRBA, a young Czech mate can, is favourited about as often as Red Bull Zero on Rohlik. That suggests Czech demand for a mate energy can is real, and that **YEAHRBA already has it.**

Ranked complaint themes can't be produced honestly from this. `/founder-consumer` should treat taste, price and effect as hypotheses to test, not as known complaints.

## 5. The gap

**There is a gap, but it is narrow, and the evidence for it is the ingredient lists, not customer complaints:**

> **No can on this shelf combines real brewed yerba mate as the only caffeine source with no added sugar and no sweetener.**

- Every mate drink in the table adds sugar, syrup, agave or honey (YEAHRBA, Club-Mate, Erebos, Voelkel, Seicha).
- Most add stimulants beyond the mate leaf: guarana, kola or isolated caffeine (YEAHRBA, Club-Mate, Erebos).
- The one unsweetened, sweetener-free can, CANS+, gets its caffeine from coffee at a low dose. Its line "Bez cukru. Bez sladidel." shows that a Czech brand can sell unsweetened, functional drinks in cans.
- Most of the natural competitors come in glass. Only YEAHRBA and CANS+ are in cans.

**This gap only holds if yerby's label actually wins on both points:** say, under ~2 g sugar/100 ml from the fruit alone, and a printed caffeine figure that energy-drink buyers respect. If the citrus concentrates bring the sugar close to YEAHRBA's 4.9 g, or the caffeine lands near CANS+'s 42 mg, then yerby is a pricier YEAHRBA and the gap is gone. **Measure both before launch.**

The provocation against matcha is aimed at a weak rival. Seicha's matcha drinks are 46.90 glass bottles with cane sugar. The rivals that actually matter for yerby are **YEAHRBA** (same format, same country, same claim, 15 CZK cheaper) and **CANS+** (same "clean" promise, in a can).

## 6. The threat: who could copy yerby fastest

1. **YEAHRBA.** It already has a Czech mate energy can, distribution on Rohlik and Dr.Max, and a "bez chemie" claim. A "zero sugar" flavour is one recipe change for them. It's the most likely copier and the most dangerous.
2. **CANS.** The brand already sells unsweetened, sweetener-free canned drinks with a functional line, under a well-known founder ([product page](https://www.rohlik.cz/1480796)). Adding a mate SKU fits its range.
3. **Mainstream brands** (Big Shock's "Smart Energy" line, Red Bull, Monster) have the distribution to launch a "natural" variant, but nothing on this shelf shows them doing so yet.
4. **yerby's own contract producer** (the board's Monopoly-lens concern) could make the same recipe for someone else. Check whether the production contract restricts that.

## What to do about the gap in this research

- **Reviews.** These four hosts were blocked from this session: rohlik.cz, heureka.sk, slevomat.cz and zbozi.cz. Rerun this step with them allowed, or paste the reviews from the YEAHRBA, Club-Mate and Erebos pages yourself. That would turn section 4 into real ranked complaints.
- **On-trade prices.** Café and bistro menu prices for Club-Mate and YEAHRBA in your target city are the comparison that matters for the B2B channel. Rohlik is retail only.
