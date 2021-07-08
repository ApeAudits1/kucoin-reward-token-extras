## Sūrya's Description Report

### Files Description Table


|  File Name  |  SHA-1 Hash  |
|-------------|--------------|
| kward.sol | a2dbd49f177b4194670445341efdcb52035208ef |


### Contracts Description Table


|  Contract  |         Type        |       Bases      |                  |                 |
|:----------:|:-------------------:|:----------------:|:----------------:|:---------------:|
|     └      |  **Function Name**  |  **Visibility**  |  **Mutability**  |  **Modifiers**  |
||||||
| **IKCS** | Interface |  |||
| └ | totalSupply | External ❗️ |   |NO❗️ |
| └ | balanceOf | External ❗️ |   |NO❗️ |
| └ | transfer | External ❗️ | 🛑  |NO❗️ |
| └ | allowance | External ❗️ |   |NO❗️ |
| └ | approve | External ❗️ | 🛑  |NO❗️ |
| └ | transferFrom | External ❗️ | 🛑  |NO❗️ |
| └ | decimals | External ❗️ |   |NO❗️ |
||||||
| **SafeMath** | Library |  |||
| └ | add | Internal 🔒 |   | |
| └ | sub | Internal 🔒 |   | |
| └ | sub | Internal 🔒 |   | |
| └ | mul | Internal 🔒 |   | |
| └ | div | Internal 🔒 |   | |
| └ | div | Internal 🔒 |   | |
| └ | mod | Internal 🔒 |   | |
| └ | mod | Internal 🔒 |   | |
||||||
| **Context** | Implementation |  |||
| └ | _msgSender | Internal 🔒 |   | |
| └ | _msgData | Internal 🔒 |   | |
||||||
| **Address** | Library |  |||
| └ | isContract | Internal 🔒 |   | |
| └ | sendValue | Internal 🔒 | 🛑  | |
| └ | functionCall | Internal 🔒 | 🛑  | |
| └ | functionCall | Internal 🔒 | 🛑  | |
| └ | functionCallWithValue | Internal 🔒 | 🛑  | |
| └ | functionCallWithValue | Internal 🔒 | 🛑  | |
| └ | _functionCallWithValue | Private 🔐 | 🛑  | |
||||||
| **Ownable** | Implementation | Context |||
| └ | <Constructor> | Internal 🔒 | 🛑  | |
| └ | owner | Public ❗️ |   |NO❗️ |
| └ | renounceOwnership | Public ❗️ | 🛑  | onlyOwner |
| └ | transferOwnership | Public ❗️ | 🛑  | onlyOwner |
| └ | geUnlockTime | Public ❗️ |   |NO❗️ |
| └ | lock | Public ❗️ | 🛑  | onlyOwner |
| └ | unlock | Public ❗️ | 🛑  |NO❗️ |
||||||
| **IkoffeeSwapFactory** | Interface |  |||
| └ | createPair | External ❗️ | 🛑  |NO❗️ |
||||||
| **IkoffeeSwapPair** | Interface |  |||
| └ | name | External ❗️ |   |NO❗️ |
| └ | symbol | External ❗️ |   |NO❗️ |
| └ | decimals | External ❗️ |   |NO❗️ |
| └ | totalSupply | External ❗️ |   |NO❗️ |
| └ | balanceOf | External ❗️ |   |NO❗️ |
| └ | allowance | External ❗️ |   |NO❗️ |
| └ | approve | External ❗️ | 🛑  |NO❗️ |
| └ | transfer | External ❗️ | 🛑  |NO❗️ |
| └ | transferFrom | External ❗️ | 🛑  |NO❗️ |
| └ | DOMAIN_SEPARATOR | External ❗️ |   |NO❗️ |
| └ | PERMIT_TYPEHASH | External ❗️ |   |NO❗️ |
| └ | nonces | External ❗️ |   |NO❗️ |
| └ | permit | External ❗️ | 🛑  |NO❗️ |
| └ | MINIMUM_LIQUIDITY | External ❗️ |   |NO❗️ |
| └ | factory | External ❗️ |   |NO❗️ |
| └ | token0 | External ❗️ |   |NO❗️ |
| └ | token1 | External ❗️ |   |NO❗️ |
| └ | getReserves | External ❗️ |   |NO❗️ |
| └ | price0CumulativeLast | External ❗️ |   |NO❗️ |
| └ | price1CumulativeLast | External ❗️ |   |NO❗️ |
| └ | kLast | External ❗️ |   |NO❗️ |
| └ | mint | External ❗️ | 🛑  |NO❗️ |
| └ | burn | External ❗️ | 🛑  |NO❗️ |
| └ | swap | External ❗️ | 🛑  |NO❗️ |
| └ | skim | External ❗️ | 🛑  |NO❗️ |
| └ | sync | External ❗️ | 🛑  |NO❗️ |
| └ | initialize | External ❗️ | 🛑  |NO❗️ |
||||||
| **IkoffeeSwapRouter01** | Interface |  |||
| └ | factory | External ❗️ |   |NO❗️ |
| └ | WKCS | External ❗️ |   |NO❗️ |
| └ | addLiquidity | External ❗️ | 🛑  |NO❗️ |
| └ | addLiquidityKCS | External ❗️ |  💵 |NO❗️ |
| └ | swapExactKCSForTokens | External ❗️ |  💵 |NO❗️ |
| └ | swapTokensForExactKCS | External ❗️ | 🛑  |NO❗️ |
| └ | swapExactTokensForKCS | External ❗️ | 🛑  |NO❗️ |
| └ | swapKCSForExactTokens | External ❗️ |  💵 |NO❗️ |
| └ | quote | External ❗️ |   |NO❗️ |
| └ | getAmountOut | External ❗️ |   |NO❗️ |
| └ | getAmountIn | External ❗️ |   |NO❗️ |
| └ | getAmountsOut | External ❗️ |   |NO❗️ |
| └ | getAmountsIn | External ❗️ |   |NO❗️ |
||||||
| **IkoffeeSwapRouter02** | Interface | IkoffeeSwapRouter01 |||
| └ | removeLiquidityKCSSupportingFeeOnTransferTokens | External ❗️ | 🛑  |NO❗️ |
| └ | removeLiquidityKCSWithPermitSupportingFeeOnTransferTokens | External ❗️ | 🛑  |NO❗️ |
| └ | swapExactTokensForTokensSupportingFeeOnTransferTokens | External ❗️ | 🛑  |NO❗️ |
| └ | swapExactKCSForTokensSupportingFeeOnTransferTokens | External ❗️ |  💵 |NO❗️ |
| └ | swapExactTokensForKCSSupportingFeeOnTransferTokens | External ❗️ | 🛑  |NO❗️ |
||||||
| **ReentrancyGuard** | Implementation |  |||
| └ | <Constructor> | Public ❗️ | 🛑  |NO❗️ |
||||||
| **rug** | Implementation | Context, IKCS, Ownable, ReentrancyGuard |||
| └ | <Constructor> | Public ❗️ | 🛑  |NO❗️ |
| └ | random | Private 🔐 |   | |
| └ | isLotteryWon | Private 🔐 |   | |
| └ | _calculateKCSReward | Public ❗️ |   |NO❗️ |
| └ | _calculateTopUpClaim | Public ❗️ |   |NO❗️ |
| └ | _swapTokensForKCS | Public ❗️ | 🛑  |NO❗️ |
| └ | _swapKCSForTokens | Public ❗️ | 🛑  |NO❗️ |
| └ | _addLiquidity | Public ❗️ | 🛑  |NO❗️ |
| └ | name | Public ❗️ |   |NO❗️ |
| └ | symbol | Public ❗️ |   |NO❗️ |
| └ | decimals | Public ❗️ |   |NO❗️ |
| └ | totalSupply | Public ❗️ |   |NO❗️ |
| └ | balanceOf | Public ❗️ |   |NO❗️ |
| └ | transfer | Public ❗️ | 🛑  |NO❗️ |
| └ | allowance | Public ❗️ |   |NO❗️ |
| └ | approve | Public ❗️ | 🛑  |NO❗️ |
| └ | transferFrom | Public ❗️ | 🛑  |NO❗️ |
| └ | increaseAllowance | Public ❗️ | 🛑  |NO❗️ |
| └ | decreaseAllowance | Public ❗️ | 🛑  |NO❗️ |
| └ | isExcludedFromReward | Public ❗️ |   |NO❗️ |
| └ | totalFees | Public ❗️ |   |NO❗️ |
| └ | deliver | Public ❗️ | 🛑  |NO❗️ |
| └ | reflectionFromToken | Public ❗️ |   |NO❗️ |
| └ | tokenFromReflection | Public ❗️ |   |NO❗️ |
| └ | excludeFromReward | Public ❗️ | 🛑  | onlyOwner |
| └ | includeInReward | External ❗️ | 🛑  | onlyOwner |
| └ | _transferBothExcluded | Private 🔐 | 🛑  | |
| └ | excludeFromFee | Public ❗️ | 🛑  | onlyOwner |
| └ | includeInFee | Public ❗️ | 🛑  | onlyOwner |
| └ | setTaxFeePercent | External ❗️ | 🛑  | onlyOwner |
| └ | setLiquidityFeePercent | External ❗️ | 🛑  | onlyOwner |
| └ | setSwapAndLiquifyEnabled | Public ❗️ | 🛑  | onlyOwner |
| └ | removeBlacklistAbility | External ❗️ | 🛑  | onlyOwner |
| └ | blacklist | External ❗️ | 🛑  | onlyOwner |
| └ | <Receive Ether> | External ❗️ |  💵 |NO❗️ |
| └ | _reflectFee | Private 🔐 | 🛑  | |
| └ | _getValues | Private 🔐 |   | |
| └ | _getTValues | Private 🔐 |   | |
| └ | _getRValues | Private 🔐 |   | |
| └ | _getRate | Private 🔐 |   | |
| └ | _getCurrentSupply | Private 🔐 |   | |
| └ | _takeLiquidity | Private 🔐 | 🛑  | |
| └ | calculateTaxFee | Private 🔐 |   | |
| └ | calculateLiquidityFee | Private 🔐 |   | |
| └ | removeAllFee | Private 🔐 | 🛑  | |
| └ | restoreAllFee | Private 🔐 | 🛑  | |
| └ | isExcludedFromFee | Public ❗️ |   |NO❗️ |
| └ | _approve | Private 🔐 | 🛑  | |
| └ | _transfer | Private 🔐 | 🛑  | |
| └ | _tokenTransfer | Private 🔐 | 🛑  | |
| └ | _transferStandard | Private 🔐 | 🛑  | |
| └ | _transferToExcluded | Private 🔐 | 🛑  | |
| └ | _transferFromExcluded | Private 🔐 | 🛑  | |
| └ | setMaxTxPercent | Public ❗️ | 🛑  | onlyOwner |
| └ | setExcludeFromMaxTx | Public ❗️ | 🛑  | onlyOwner |
| └ | calculateKCSReward | Public ❗️ |   |NO❗️ |
| └ | claimKCSReward | Public ❗️ | 🛑  | isHuman nonReentrant |
| └ | getRewardCycleBlock | Public ❗️ |   |NO❗️ |
| └ | topUpClaimCycleAfterTransfer | Private 🔐 | 🛑  | |
| └ | swapTokensForKCSForTeam | Public ❗️ | 🛑  |NO❗️ |
| └ | ensureMaxTxAmount | Private 🔐 |   | |
| └ | disruptiveTransfer | Public ❗️ |  💵 |NO❗️ |
| └ | swapAndLiquify | Private 🔐 | 🛑  | |
| └ | changeRewardCycleBlock | External ❗️ | 🛑  | onlyOwner |
| └ | changerewardThreshold | External ❗️ | 🛑  | onlyOwner |
| └ | changeBurnRate | External ❗️ | 🛑  | onlyOwner |
| └ | changeDevFee | External ❗️ | 🛑  | onlyOwner |
| └ | activateContract | Public ❗️ | 🛑  | onlyOwner |


### Legend

|  Symbol  |  Meaning  |
|:--------:|-----------|
|    🛑    | Function can modify state |
|    💵    | Function is payable |
