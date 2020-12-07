# Liquidity on WanSwap Explained

In this article, we will explain how liquidity works on WanSwap.

![](https://cdn-images-1.medium.com/max/2000/1*Sf-MLrS4pkAWEzqVg4enPg.png)

**Introduction to liquidity pools**

When you supply liquidity to a WanSwap liquidity pool, you receive WSLP tokens in proportion to how much liquidity you supply to the pool. When a trade is facilitated by the pool a percentage of the fee is proportionally distributed amongst all the liquidity pools token holders. If you withdraw your assets from the pool, you will receive the earned fees but your tokens will be burned.

The liquidity pool token for WanSwap is WSLP, in WanSwap you can use your WSLP to withdraw your assets from the pool and it can be used for mining governance tokens: WASP.

**Liquidity mechanics**

I will explain the mechanics by using an example. Let’s say you want to provide liquidity in the WAN-wanUSDT pool. The way the pools work is you have to deposit an equal value of WAN and the token that you want to participate with, in this case, wanUSDT.

It’s advised to do some research when adding liquidity in the pool, always check if the value is like it should be. Enter the amount of one of the assets into the field, it calculates the equal amount in value of the other asset automatically. It’s important that the value is 50/50, you could change the amount but if you do this, somebody could arbitrage it and you could lose your funds.

Once you added liquidity to the pool and someone makes a swap on the pair, your liquidity will be tapped into. Based on the trade, your amount in the pool will shift towards more WAN or more wanUSDT. So if someone would have traded WAN for wanUSDC, your wanUSDC liquidity will shrink but your WAN liquidity will increase. It works like a scale, you should always come out to the same combined value as you put in.

![Source: Uniswap](https://cdn-images-1.medium.com/max/3600/1*ZT9YIcBzzFYqHPbflSWALA.jpeg)*Source: Uniswap*

The liquidity providers (LP)get a percentage of every trade that is made in the pool. It’s divided over every LP in the pool. The bigger the share you have in the pool, the larger the share of the reward you will receive. On WanSwap the transaction fee is 0.3%, 0.25% will go to the LP, and 0.05% will be used for WanSwap for buying back WASP tokens. For example: if your part in the liquidity pool is 3%, you will get 3% of the 0.25% fee.

For providing liquidity to the pool you will get WLSP tokens. The amount of tokens you get represents your share of the pool. When you withdraw from the pool these tokens will be burned.

**Impermanent Loss**

In essence, an impermanent loss is a temporary loss of funds occurring when providing liquidity. You can find a good guide about impermanent loss [here](https://finematics.com/impermanent-loss-explained/).

Make sure you are aware of impermanent loss before you jump into providing liquidity!

### **Mining WASP tokens**

**WASP** is the Wanchain based WRC20 token which will be generated for WanSwap and used for liquidity mining, governance, and other purposes. There will be a total of 210 million WASP distributed over 24 months. 95% of that will be rewarded to liquidity providers, 5% will go to the community treasury.

The WASP distribution takes place over 24 months as follows:

*Phase 1: (~1st week, according to block height) 1X rewards (~12.5286 WASP / block)*

*Phase 2:** **(around 2 months) 5X*

*Phase 3: ‘Gold Saints’ (around 21 months + 3 weeks) 1X*

You can use the WSLP tokens you receive from your share in the liquidity pool to farm WASP tokens.

The initial trading pairs are as following with different WASP reward weights:

WAN — wanBTC weight: 15%

WAN — wanEOS weight: 3%

WAN — wanETH weight: 40%

WAN — wanUSDT weight: 40%

WAN — FNX weight: 2%

WASP holders will soon be able to vote to modify the weights through the voting portal. The more WASP you hold, the bigger the impact of your vote will be.

A tutorial on how to use WanSwap’s interface can be found [here](https://medium.com/wanswap/how-to-use-wanswap-f80e206827d6).