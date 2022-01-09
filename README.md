# CCToken
A Reflective token with (tax, marketing, liquidity) fees on BSC

tax fee: 5%
marketing wallet fee: 5%
liquidity wallet fee: 5%
extra fee on sell: 2% (half for marketing wallet & liquidity wallet, respectively)
liquidity fee: 0%

------------------------------------------------------
1. Reflective fee - Rewards in Pegged Cardano
2. Marketing fee
3. Liquidity fee - that function is exactly like Marketing wallet (Funds will be added to the pool manually once a day).
4. An additional fee on sell (half to marketing wallet and half to liquidity wallet)
5. Auto LP fee when LP-token goes to liquidity wallet - this function will be on standby in case I will need it in the future, this function will be set to 0% when liquidity wallet is on and vice versa.
6. An upper limit on wallet size (maxWalletPercent)
7. An upper limit on transaction size (maxTxAmount)
8. Ability for owner to withdraw tokens from contract
9. Ability to exclude and include an address from each restriction individually or all together
