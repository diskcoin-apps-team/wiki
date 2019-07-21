##How to Stake?

From the block height of 1801, if you want to Stake, you need to do the corresponding operation in your wallet. The more DISCs you Stake, the more reward you will get.


###How to Stake:
```
./diskcoin-cli pledgeto the-wallet-address-you-Stake-to the-Stake-amount  
```

The Staking address needs to be the address that generated blocks.


###How to check the default wallet address:
```
./diskcoin-cli getaccountaddress ""
```

A hash will be returned after the Staking.


###Check the Staking records of the address:
```
listpledgein (minconf maxconf  ["address",...])
```

Minconf: minimum confirmation

Maxconf: maximum confirmation


###Cancel the Staking:
```
./diskcoin-cli unpledge txid
```

You could use the listpledgein command to get the txid that has been Staked.
After the Staking is successful, it will take effect after 900 blocks.
