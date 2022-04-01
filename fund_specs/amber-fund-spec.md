# Amber Hedge Fund Directional Specification

Fund page on dHedge with statistic: - [app.dhedge.org/pool/0xcfd380c467da78c1bd03cc63ceb9686081cc59d7](https://app.dhedge.org/pool/0xcfd380c467da78c1bd03cc63ceb9686081cc59d7)

## Fund assets under management

1. [WBTC](https://wbtc.network/) - wrapped bitcoin token to be able to have exposure on [Bitcoin](https://bitcoin.org/en/) in the [Optimistic rollup](https://www.optimism.io/) ([Ethereum L2 solution](https://ethereum.org/en/developers/docs/scaling/optimistic-rollups/)).  
2. [DAI](https://makerdao.com/en/) - [multiple asset pegged](https://en.wikipedia.org/wiki/Dai_(cryptocurrency)) stable coin to be able to have exposure to USD price. 

## Fund strategy & expected results

Strategy based on a few expectations and assumptions:
* Bitcoin network adoption.
* Cryptocurrency market growth.
* Intrinsic value of Bitcoin will continue to grow due to increasing bitcoin-related businesses and the Bitcoin name as a trademark.
* Using leverage trading increases risk disproportionately due to the high volatility of Bitcoin

Taking into account these assumptions it looks rationally to develop a strategy to increase (accumulate) Bitcoin using short-term market inefficiency and volatility. The main purpose of this fund is to outperform the simple BTC buy & hold strategy in the long term. The strategy of the fund utilizes a non-leveraged weighted rebalancing approach.
- DeFi used for assets swap: [uniswap.org](https://uniswap.org/)
- Protocol: [Optimistic rollup](https://www.optimism.io/) (significantly lower fees than on the main chain)
- Platform: [dhedge.org](https://www.dhedge.org/)

Expected returns: Bitcoin APY + ~20% (including management fee)  
Expected asset max downfall: ~15% less than BTC downfall. Bitcoin can reach an almos downfall from ATH during bear markets.  
Recommended asset allocation period: 2 years.  
Allowed investment assets: WBTC, DAI.

## Fund fees & policies

1. Performance fee depends on yearly averaged assets under management and is calculated using [High-Water Mark](https://www.investopedia.com/terms/h/highwatermark.asp). Current performance fee - 20%.

|Year averaged AUM, USD|Performance fee, %|
|:---------------------|:-----------------|
|< 10,000              |20%               |
|10,000 - 50,000       |15%               |
|50,000 -  100,000     |10%               |
|> 100,000             |5%                |

2. There are no entry, exit and other management fees to stimulate clients to hold assets for the long term.    
3. Assets are forbidden to withdraw within 24 hours after seeding for flash loans and arbitrage protection.  
4. After withdrawing all funds from the pool, users have to go through the investment application process one more time.  
5. Asset managers keep the right to disallow any investment without explaining.  
6. Invested assets withdrawal is guaranteed by the dHedge smart contract and cannot be blocked by the asset manager.

## Fund improvements

Under investigation:  
1. Move trading to synthetic sBTC and sUSD (powered by [synthetix.io](https://synthetix.io/)) using [kwenta.io](https://kwenta.io/) futures trading platform with 1x leverage. Reason: zero slippage trading with higher liquidity.

----

*Amber Assets Management does not issue nor deals with any derivatives contract or ETNs. Nothing herein constitutes an offer to sell, or the solicitation of an offer to buy, any securities or tokens. Amber Assets Management enables capital connection and managing using smart contracts which are open source. Amber Assets Management does not take custody of tokens and is only a collaborative hub for investors and managers. Amber Assets Management is not a licensed bank, broker-dealer, investment advisor, or exchange. Amber Assets Management uses partner protocols to power its own ecosystem. Before any investment decision, do your own research.*