# Silver Hill Directional Fund Specification

Fund page on dHedge with statistic: - [app.dhedge.org/pool/0x35f8a62da489b43466196329abf9c934bf6f1ff3](https://app.dhedge.org/pool/0x35f8a62da489b43466196329abf9c934bf6f1ff3)

## Fund assets under management

1. [WETH](https://weth.io/) - wrapped ethereum token to be able to have exposure on [Ethereum](https://ethereum.org/en/) in the in the [Optimistic rollup](https://www.optimism.io/) ([Ethereum L2 solution](https://ethereum.org/en/developers/docs/scaling/optimistic-rollups/)).  
2. [USDC](https://www.circle.com/en/usdc) - stable coin pegged by USD. The token is primarily promoted by [Coinbase](https://www.circle.com/en/usdc) and supported by the [CENTRE consortium](https://www.circle.com/en/usdc) 

## Fund strategy & expected results

Strategy based on few expectations and assumptions:
* Ethereum network adoption.
* Cryptocurrency market growth.
* Intrinsic value of Ethereum will continue to grow due to increasing Ethereum-related on-chain and off-chain businesses and the Ethereum name as a trademark.
* Using leverage trading increases risk disproportionately due to the high volatility of Ethereum

Taking into account these assumptions it looks rationally to develop a strategy to increase (accumulate) Ethereum using short-term market inefficiency and volatility. The main purpose of this fund is to outperform the simple ETH buy & stake (ETH 2.0) strategy. The strategy of the fund utilizes a non-leveraged weighted rebalancing approach.
- DeFi used for assets swap: [uniswap.org](https://uniswap.org/)
- Protocol: [Optimistic rollup](https://www.optimism.io/) (significantly lower fees than on the main chain)
- Platform: [dhedge.org](https://www.dhedge.org/)

Expected returns: Ethereum APY + ~30% (including management fee)
Expected asset max downfall: ~15% less than ETH downfall. Ethereum can reach an almost 90% downfall from ATH during bear markets. 
Recommended asset allocation period - 2 years.  
Allowed investment assets: WETH, USDC. 

## Fund fees & policies

1. Performance fee depends on yearly averaged assets under management and is calculated using [High-Water Mark](https://www.investopedia.com/terms/h/highwatermark.asp). Current performance fee - 20%.

|Year averaged AUM, USD|Performance fee, %|
|:---------------------|:-----------------|
|< 15,000              |20%               |
|15,000 - 65,000       |15%               |
|65,000 -  130,000     |10%               |
|> 130,000             |5%                |

2. There are no entry, exit and other management fees to stimulate clients to hold assets for the long term.  
3. Assets are forbidden to withdraw within 24 hours after seeding for flash loans and arbitrage protection.  
4. After withdrawing all funds from the pool, users have to go through the investment application process one more time.  
5. Asset managers keep the right to disallow any investment without explaining.  
6. Invested assets withdrawal is guaranteed by the dHedge smart contract and cannot be blocked by the asset manager.

## Fund improvements

Under investigation:  
1. Move trading to synthetic sETH and sUSD (powered by [synthetix.io](https://synthetix.io/)) using [kwenta.io](https://kwenta.io/) futures trading platform with 1x leverage. Reason: zero slippage trading with higher liquidity.

----

*Amber Assets Management does not issue nor deals with any derivatives contract or ETNs. Nothing herein constitutes an offer to sell, or the solicitation of an offer to buy, any securities or tokens. Amber Assets Management enables capital connection and managing using smart contracts which are open source. Amber Assets Management does not take custody of tokens and is only a collaborative hub for investors and managers. Amber Assets Management is not a licensed bank, broker-dealer, investment advisor, or exchange. Amber Assets Management uses partner protocols to power its own ecosystem. Before any investment decision, do your own research.*
