# Too Large Supply Error?

Uniswap V2 has a limit on the maximum amount of Tokens in their liquidity.  
  
For us this plays an important role, since we are about to add this liquidity for you to the Router.  
  
To make this possible please ensure to reduce your decimals if you want to go with a token with a very big supply.  
  
Max Supply + Decimals = Max Amount of Tokens in the Liquidity

![](../../.gitbook/assets/image%20%2823%29.png)

## Example:

| MaxSupply | Decimals |
| :--- | :--- |
| 10000000000000000000000000 | 000000\(6\) |
| 10000000000000000000000 | 000000000\(9\) |
| 10000000000000 | 000000000000000000\(18\) |

\(This is the Maximum, so yeah rather put a zero away\)

