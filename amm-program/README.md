# Automated Market Maker

[Open link](https://www.moonpay.com/learn/defi/what-is-an-automated-market-maker-amm) <br/>
```tl-dr```
This protocol allows for instantaneous exchange of tokens without waiting for a counterpart to complete the trade.
this is achieved 

price determination based on the constant product curve
if x represent a certain token 
if y represent another token

a Pool of x-y is created to facilitate exchange of x and y and vice versa between users
the pool must hold quantity of x and y such that they are in proportion of 1:1 based on their value

if x = $10
and y = $20

the pool must contain 2x: y

## Flow
- A Token Pair is Initialized
  - token x: 1 part of the swap pair
    - ATA to store token X for the AMM
  - token y: 1 part of the swap pair
    - ATA to store token Y for the AMM

- Mint LP: the mint account that would be used to reward the Liquidity Provider
- Config: Account holding configuration for the pair