---
description: >-
  Uniswap V2 has a limit on the maximum amount of Tokens in their liquidity.
  This will explain why you should be mindful of this
---

# Other: Way too large of token supply

Due to Uniswap V2's limit (which is copied by most AMMs) , you will need to reduce the total supply of tokens. To make this possible, please ensure to reduce your decimals if you want to go with a token with a very big supply.

{% hint style="info" %}
Max Supply + Decimals = Max Amount of Tokens in the Liquidity
{% endhint %}



![](<../../.gitbook/assets/image (35).png>)

## Example:

| MaxSupply                  | Decimals               |
| -------------------------- | ---------------------- |
| 10000000000000000000000000 | 000000(6)              |
| 10000000000000000000000    | 000000000(9)           |
| 10000000000000             | 000000000000000000(18) |

