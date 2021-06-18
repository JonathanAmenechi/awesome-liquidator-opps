# awesome-liquidator-opps


List of Protocols with liquidator opportunities. Inspired by https://twitter.com/tomhschmidt/status/1405322722930876420?s=20



| Protocol           | Network                  | Links   | Liquidation Mechanism  | Protocol category      |Liquidator Incentive|
|:-------------------|:------------------------ |:---------|:------|:-----------------------|:--------------------|
|[MakerDAO](https://makerdao.com/en/)|[Ethereum](https://ethereum.org/en/)|[Github](https://github.com/makerdao), [Basic overview](https://community-development.makerdao.com/en/learn/vaults/liquidation/) [Detailed Liquidations overview](https://docs.makerdao.com/smart-contract-modules/dog-and-clipper-detailed-documentation)|Dutch Auction|Stablecoin Generator|13%|
|[Compound](https://compound.finance/)|[Ethereum](https://ethereum.org/en/)|[Github](https://github.com/compound-finance/compound-protocol), [Docs](https://compound.finance/docs/comptroller#liquidation-incentive)|Fixed Discount, First Come, First Served|Money Market            |8% of borrower's collateral|
|[Aave](https://aave.com/)|[Ethereum](https://ethereum.org/en/), [Polygon](https://polygon.technology/)|[Github](https://github.com/aave/protocol-v2), [Risk Docs](https://docs.aave.com/risk/asset-risk/risk-parameters)|Fixed Discount, FCFS|Money Market            |Variable depending on the asset|
|[Liquity](https://liquity.fi/)|[Ethereum](https://ethereum.org/en/)|[Liquidation overview](https://docs.liquity.org/faq/stability-pool-and-liquidations)|Backstop pool of LUSD burned in liqs, keepers earn fee for triggering the txn, FCFS|Stablecoin Generator|200 LUSD + 0.5%|
|[Alpha Homora](https://alphafinance.io)|[Ethereum](https://ethereum.org/en/), [BSC](https://www.binance.org/en/smartChain)|[V2 Docs](https://alphafinancelab.gitbook.io/alpha-homora-v2/liquidators/untitled#how-to-liquidate-a-position-and-earn-bounty), [V1 Docs](https://alphafinancelab.gitbook.io/alpha-homora/what-is-alpha-homora)|Fixed Discount, FCFS|Levered LP|5%|
|[Synthetix](https://synthetix.io/)|[Ethereum](https://ethereum.org/en/)|[Github](https://github.com/Synthetixio/synthetix)|Fixed Discount, FCFS|Synthetic asset platform|10%, 3 day liq delay|
|C.r.e.a.m Finance   |Ethereum, BSC             |          |Fixed Discount, FCFS|Money Market            ||
|Dydx                |Ethereum, Starkware       |          |       |Exchange                ||
|UMA                 |Ethereum                  |          |       |Synthetic Assets        ||
|[Reflexer](https://reflexer.finance/)|[Ethereum](https://ethereum.org/en/)|[Docs](https://docs.reflexer.finance/), [Github](https://github.com/reflexer-labs/geb), [Stats](https://stats.reflexer.finance/)|Fixed Discount, FCFS|Stablecoin Generator|12%|
|[Kashi](https://github.com/sushiswap/kashi-lending)|[Ethereum](https://ethereum.org/en/), [BSC](https://www.binance.org/en/smartChain)|[Github](https://github.com/sushiswap/kashi-lending), [Docs](https://docs.sushi.com/products/kashi-lending)|Fixed Discount, FCFS|Isolated Lending|12%|
|[Fuse](https://app.rari.capital/fuse/)|[Ethereum](https://ethereum.org/en/)|[Github](https://github.com/Rari-Capital/compound-protocol), [Docs](https://docs.rari.capital/fuse/#liquidate-borrow)|Fixed Discount, FCFS|Isolated Lending Pools|Variable across pools|
|[Anchor](https://inverse.finance/banking)      |[Ethereum](https://ethereum.org/en/)|[Github](https://github.com/InverseFinance/anchor), [Liquidation Overview](https://docs.inverse.finance/user-guides/anchor-lending-and-borrowing/liquidations)|Fixed Discount, FCFS|Money Market|13%|
|Notional            |Ethereum                  |          |       |Fixed Term Lender       ||
|Yield Protocol      |Ethereum                  |          |       |Fixed Term Lender       ||
|Unit Protocol       |Ethereum, BSC             |          |       |Stablecoin Generator    ||