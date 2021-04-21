*An UMIP number will be assigned by an editor. When opening a pull request to submit your UMIP, please use an abbreviated title in the filename. The file name should follow this format - "umip_add_priceidentifiername_priceid.md". Please remove this and all italicized instructions before submitting your pr. All bolded fields should be filled in before submission.*

## HEADERS

| UMIP                |                                                               |
| ------------------- | ------------------------------------------------------------- |
| UMIP Title          | Add **Price Identifier Name** as a supported price identifier |
| Authors             | **Name**                                                      |
| Status              | Draft                                                         |
| Created             | **Today's Date**                                              |
| Discourse Link      | **Discourse Link**                                            |

# SUMMARY 

The DVM should support price requests for **Price Identifier Name**. **Price Identifier name** reflects the **Summary of Price Identifier**.


# MOTIVATION

*Please explain why you want to add this price identifier. What types of synthetics are you intending to create with this?*

# MARKETS & DATA SOURCES

*How should voters access the data necessary to calculate the value of this price identifier? What specific markets should be referenced?*

-----------------------------------------
- Price identifier name: **First Price ID Name** 
- Markets & Pairs: **Markets & Pairs** - *Example: Binance ETH/USDT, Coinbase Pro ETH/USD*
- Example price providers: **Provider to use** - *Cryptowatch, TraderMade, Quandl, the Graph*
- Cost to use: **Explanation or link to provider pricing plan**
- Real-time price update frequency: **Frequency** - *60 seconds*
- Historical price update frequency: **Frequency** - *5 minutes*

# PRICE FEED IMPLEMENTATION

*To allow for the creation of bots that can programmatically calculate prices off-chain to liquidate and dispute transactions, you must create a price feed following the UMA Protocol format (outlined below). This price feed is also necessary to calculate developer mining rewards.*

*If using existing price feeds from the [UMA protocol repo](https://github.com/UMAprotocol/protocol/tree/master/packages/financial-templates-lib/src/price-feed), please list the price feeds used and write a price feed configuration following the examples [here](https://github.com/UMAprotocol/protocol/blob/master/packages/financial-templates-lib/src/price-feed/DefaultPriceFeedConfigs.js).*


Existing price feeds include *Please remove before submission*:
- Balancer
- Uniswap/SushiSwap
- CoinGecko
- CoinMarketCap
- CryptoWatch
- DefiPulse
- TraderMade Forex rates
- ExchangeRate Forex rates
- LP token prices
- Vault token prices
- Quandl
- Any combination of these

# TECHNICAL SPECIFICATIONS

-----------------------------------------
- Price identifier name: **First Price ID Name** 
- Base Currency: **Markets & Pairs** - *Example: Binance ETH/USDT, Coinbase Pro ETH/USD*
- Quote Currency: **Provider to use** - *Cryptowatch, TraderMade, Quandl, the Graph*
- Rounding: *Round to 2 decimal places*
- Current Value of Price Identifier: *15.03*

# RATIONALE

*The section should describe why price identifier design decisions were made, as well as any alternative designs that were considered.*

# IMPLEMENTATION

Describe how UMA tokenholders should arrive at the price in the case of a DVM price request. Document each step a voter should take to query for and return a price at a specific timestamp. Include the following in the description:

# Security considerations

Some optional questions to consider *Please remove before submission*:
- How could price manipulation occur?
- How could this price ID be exploited?
- Do the instructions for determining the price provide people with enough certainty?
- What are current or future concern possibilities with the way the price identifier is defined?
- Are there any concerns around if the price identifier implementation is deterministic?
