# Research Sample: Tokenized Private Credit

*Sample research note. Figures are drawn from public reports cited inline and are dated; market-size definitions in this sector differ widely between sources, and those differences are part of the analysis rather than noise to hide.*

## Thesis

The tokenization story was supposed to be about Treasury bills. Instead, by early 2026 private credit had quietly become the largest category of on-chain real-world assets. The driver is structural, not speculative: banks have retreated from mid-market lending, a multi-trillion-dollar private credit market needs new distribution, and idle stablecoin balances need yield. Tokenization is where those three meet. It is also the first tokenized category that can transmit a real credit cycle on-chain.

## Why the headline numbers disagree

Published estimates for tokenized private credit range from under $1B to over $18B depending on the source. The gap is definitional:

- **Permissioned record-keeping** (for example, HELOC volume recorded on a permissioned chain) counts loans originated through a platform, most of which are not composable DeFi assets
- **Distributed on-chain value** counts tokens actually held in wallets on public chains
- **Cumulative origination** counts everything ever issued, including repaid loans

Any honest market sizing has to state which definition it is using. This note uses distributed on-chain value where available and says so.

## Drivers

1. **Off-chain credit gap.** Registered-fund holdings of private credit grew from roughly $170B (Dec 2020) to roughly $270B (Dec 2025) in SEC-cited data, and the broader private credit market is larger still. Borrowers pay for speed and certainty that banks no longer offer.
2. **Stablecoin demand for yield.** Stablecoins settle payments but do not pass through risk-free yield. Senior tranches of tokenized credit products have advertised indicative yields in the 8-15% range (indicative only, not guaranteed), which is the demand engine.
3. **Institutional entry.** Apollo's ACRED (via Securitize), Centrifuge's Janus Henderson partnership, and Maple's institutional lending pools show the category is no longer DeFi-native only.

## Representative platforms

| Platform | Model | Note |
| --- | --- | --- |
| Figure | HELOC origination, permissioned chain | Largest by recorded volume; not DeFi-composable |
| Maple Finance | Institutional lending pools, syrupUSDC | Survived 2022 credit losses; rebuilt with over-collateralized products |
| Centrifuge | Receivables and structured credit | Institutional partnerships (Janus Henderson JAAA) |
| Apollo ACRED via Securitize | Tokenized feeder into Apollo credit funds | Traditional manager distribution on-chain |

## Risks that tokenization does not remove

- **Credit risk.** The 2022 cycle already produced defaults in on-chain lending (Maple and TrueFi pools, Goldfinch emerging-market exposure). Putting a loan on-chain makes it transparent and transferable; it does not make the borrower more likely to repay.
- **Valuation.** Underlying loans have no market quote. NAV is model-based, and SEC staff have specifically cautioned (Rule 2a-5 fair-value context) that daily token prices can create false precision for assets that do not trade.
- **Access limits.** Most institutional product requires KYC and accredited status, so "democratized access" is only partly true today.
- **Composability contagion.** The same feature that makes tokenized credit useful as DeFi collateral can transmit an off-chain credit event into on-chain liquidations quickly.

## What would confirm or break the supercycle

Watch, in order: realized default rates through a full credit cycle; the share of institutional (not retail) capital; secondary-market depth for the tokens themselves. If those three hold up, private credit is the durable category. If defaults arrive while exit liquidity is still thin, it becomes the cautionary tale instead.

## Conclusion

Treasuries tokenized cash. Private credit is tokenizing lending itself. That is why it leads the category, and why it will be tested first.

*Not financial advice. Primary sources to re-check before republication: rwa.xyz category data (dated at time of reading), SEC staff statements on private credit fund holdings and fair value, platform disclosures for Figure, Maple, Centrifuge, and Securitize/Apollo.*
