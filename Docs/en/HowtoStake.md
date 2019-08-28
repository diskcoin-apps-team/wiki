## How to Stake?

From the block height of 1801, if you want to Stake, you need to do the corresponding operation in your wallet. The more DISCs you Stake, the more reward you will get. After you Stake, it will take effect in the next block. After you unstake, it will take effect after 900 blocks.


### Linux system：
#### How to Stake:
```
./diskcoin-cli staketo the-wallet-address-you-stake-to the-stake-amount  
```

The Staking address needs to be the address that generated blocks.


#### How to check the default wallet address:
```
./diskcoin-cli getaccountaddress ""
```

A hash will be returned after the Staking.


#### Check the Staking records of the address:
```
liststakein (minconf maxconf  ["address",...])
```

Minconf: minimum confirmation

Maxconf: maximum confirmation


#### Cancel the Staking:
```
./diskcoin-cli unstake txid
```

You could use the listStakein command to get the txid that has been Staked.


### Windows/MacOS system (Taking the MacOS system as an example, the Windows system is the same operation)
#### How to Stake:
Launch the wallet, click on “Send” in the upper navigation bar, fill in the address you want to Stake in the "Stake to" line, and fill in the amount you want to Stake in "Amount". Make sure the bottom left is Stake to, click send.
![alt](image/Staketo.jpg)


#### How to check the records of Staked:
You can find the record of Staked in "Transactions". As the picture shows.
![alt](image/Transactions.jpg)


#### How to cancel the Stake:
Select the record you want to cancel Stake, click the right mouse button and select unstake.
![alt](image/unstake.jpg)
