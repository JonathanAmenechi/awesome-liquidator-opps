# awesome-liquidator-opps


List of Protocols with liquidator opportunities. Inspired by https://twitter.com/tomhschmidt/status/1405322722930876420?s=20



| Protocol           | Network                  | Links   | Liquidation Mechanism  |Liquidator Incentive|Keeper Capital Requirements|Reference Keeper Implementation|
|:-------------------|:------------------------ |:---------|:------|:-----------------------|:---------------------|:----------------------------------|
|[MakerDAO](https://makerdao.com/en/)|[Ethereum](https://ethereum.org/en/)|[Github](https://github.com/makerdao), [Basic overview](https://community-development.makerdao.com/en/learn/vaults/liquidation/) [Detailed Liquidations overview](https://docs.makerdao.com/smart-contract-modules/dog-and-clipper-detailed-documentation)|Dutch Auction|13%|Liq 2.0: None, Flashloanable ⚡|[Liq 2.0 Reference Keeper](https://github.com/makerdao/auction-demo-keeper)|
|[Compound](https://compound.finance/)|[Ethereum](https://ethereum.org/en/)|[Github](https://github.com/compound-finance/compound-protocol), [Docs](https://compound.finance/docs/comptroller#liquidation-incentive)|Fixed Discount, First Come, First Served|8% of borrower's collateral|Flashloanable ⚡||
|[Aave](https://aave.com/)|[Ethereum](https://ethereum.org/en/), [Polygon](https://polygon.technology/)|[Github](https://github.com/aave/protocol-v2), [Risk Docs](https://docs.aave.com/risk/asset-risk/risk-parameters)|Fixed Discount, FCFS|Variable depending on the asset|Flashloanable ⚡||
|[Liquity](https://liquity.fi/)|[Ethereum](https://ethereum.org/en/)|[Liquidation overview](https://docs.liquity.org/faq/stability-pool-and-liquidations)|Backstop pool of LUSD burned in liqs, keepers earn fee for triggering the txn, FCFS|200 LUSD + 0.5%|None, capital risk taken by backstop pool||
|[Alpha Homora](https://alphafinance.io)|[Ethereum](https://ethereum.org/en/), [BSC](https://www.binance.org/en/smartChain)|[V2 Docs](https://alphafinancelab.gitbook.io/alpha-homora-v2/liquidators/untitled#how-to-liquidate-a-position-and-earn-bounty), [V1 Docs](https://alphafinancelab.gitbook.io/alpha-homora/what-is-alpha-homora)|Fixed Discount, FCFS|5%|?||
|[Synthetix](https://synthetix.io/)|[Ethereum](https://ethereum.org/en/)|[Github](https://github.com/Synthetixio/synthetix)|Fixed Discount, FCFS|10%, 3 day liq delay|?||
|[C.R.E.A.M Finance](https://cream.finance/)|[Ethereum](https://ethereum.org/en/), [BSC](https://www.binance.org/en/smartChain), [Polygon](https://polygon.technology/)|[Docs](https://docs.cream.finance/developer/crtokens#liquidate-borrow), [Github](https://github.com/CreamFi/compound-protocol)|Fixed Discount, FCFS|[8%](https://etherscan.io/readContract?m=normal&a=0x3d5BC3c8d13dcB8bF317092d84783c2697AE9258&v=0x4b147984b0314260fda782a7f508749df4e5a083#readCollapse29)|Flashloanable ⚡||
|[Dydx](https://dydx.exchange/)|[Ethereum](https://ethereum.org/en/), [Starkware](https://starkware.co/product/starkex/)|          |       |||
|UMA                 |Ethereum                  |          |       |||
|[Reflexer](https://reflexer.finance/)|[Ethereum](https://ethereum.org/en/)|[Docs](https://docs.reflexer.finance/), [Github](https://github.com/reflexer-labs/geb), [Stats](https://stats.reflexer.finance/)|Fixed Discount, FCFS|12%|Flashloanable ⚡|[Geb Auction Keeper](https://github.com/reflexer-labs/auction-keeper)|
|[Kashi](https://github.com/sushiswap/kashi-lending)|[Ethereum](https://ethereum.org/en/), [BSC](https://www.binance.org/en/smartChain)|[Github](https://github.com/sushiswap/kashi-lending), [Docs](https://docs.sushi.com/products/kashi-lending)|Fixed Discount, FCFS|12%|?||
|[Fuse](https://app.rari.capital/fuse/)|[Ethereum](https://ethereum.org/en/)|[Github](https://github.com/Rari-Capital/compound-protocol), [Docs](https://docs.rari.capital/fuse/#liquidate-borrow)|Fixed Discount, FCFS|Variable across pools|Flashloanable ⚡|[Fuse Liquidator](https://github.com/Rari-Capital/fuse-liquidator-bot)|
|[Anchor](https://inverse.finance/banking)      |[Ethereum](https://ethereum.org/en/)|[Github](https://github.com/InverseFinance/anchor), [Liquidation Overview](https://docs.inverse.finance/user-guides/anchor-lending-and-borrowing/liquidations)|Fixed Discount, FCFS|13%|Flashloanable ⚡||
|Notional            |Ethereum                  |          |       ||||
|[Yield Protocol](https://yield.is/)|[Ethereum](https://ethereum.org/en/)|[Github](https://github.com/yieldprotocol), [V1 Docs](https://docs.yield.is/developers/contracts/liquidations.html)|       ||||
|Unit Protocol       |Ethereum, BSC             |          |       ||||
|[Mai Finance](https://www.mai.finance/)|[Polygon](https://polygon.technology/)|[Liquidation Docs](https://docs.mai.finance/liquidation), [Github](https://github.com/0xlaozi/qidao), [Stats](https://app.mai.finance/analytics)|Fixed Discount, Partial Liquidations only, FCFS|5% of borrowers collateral(can only liq half of collateral at 10% liq penalty)|?||