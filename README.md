# ARTStroio
Gitcoin Bug Fixes for: https://gitcoin.co/issue/artstroio/dapp/2/100025505

==================================
ARTStroio React App:
==================================

Generated Reacct App from previous version of artstroio.io 

==================================
Bug Fixes:
==================================

"Tokens NOT SHOWING":

1 - Capital letters was misspelling the account address.
- example: account: 0x000a0b0c was loading : 0x000A0B0C this was generating a bug on addresses.

2 - String was beeing compared with type object instead the objects value (string inside).



==================================
How to use Mainnet or TestNet?
==================================

Just change the >>>link address<<< on web3.js (line 739) to testnet or mainnet.

Find-Token NOT FOUND:

onLoad.Window function was overloading and not detecting walletAddress. 
To fix that we need to add an html field "Acc1" with the address on it's value parameter.


