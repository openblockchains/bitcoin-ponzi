Token sales! Initial coin offerings (ICOs)! Free easy money!

# Awesome (Get-Rich-Quick) Tokens

A collection on how to build / run / issue / mint / print your own awesome (get-rich-quick) tokens in five / twenty / ninety minutes.


_Contributions welcome. Anything missing? Send in a pull request. Thanks._



## Ethereum Standard #20 Token

_ERC20 = Ethereum Request for Comments (ERC) #20 - Fungible Tokens_


### Intro

To create your very own token in five minutes you need four pieces:

|                                       | Example        |
|---------------------------------------|----------------|
| 1. Name of the token                  | Your Krypto Token |
| 2. Token symbol (like a stock ticker) | YOU                 |
| 3. Token decimal places (making the token divisible) | 2   |
| 4. Total number of tokens in circulation | 2 100 000 000   |


That's it. 

``` Solidity
contract YourToken is StandardToken {
    string public constant name    = 'Your Krypto Token';
    string public constant symbol  = 'YOU';
    uint8 public constant decimals = 2;
    uint constant _initial_supply  = 2100000000;

    function YourToken() public {
        totalSupply_         = _initial_supply;
        balances[msg.sender] = _initial_supply;
        Transfer(address(0), msg.sender, _initial_supply);
    }
}
```


### How-To Articles


[**How to deploy an ERC20 token in 20 minutes**](http://www.masonforest.com/blockchain/ethereum/2017/11/13/how-to-deploy-an-erc20-token-in-20-minutes.html) 
by Mason Fischer, November 2017

[**How to build your own Ethereum based ERC20 Token and launch an initial coin offering (ICO) in next 20 minutes**](https://hashnode.com/post/how-to-build-your-own-ethereum-based-erc20-token-and-launch-an-ico-in-next-20-minutes-cjbcpwzec01c93awtbij90uzn)
by Sandeep Panda, December 2017

[**How to issue your own token on Ethereum in less than 20 minutes**](https://medium.com/bitfwd/how-to-issue-your-own-token-on-ethereum-in-less-than-20-minutes-ac1f8f022793) 
by Moritz Neto, December 2017

[**How to Launch an initial coin offering (ICO) Token on Ethereum in 90 Minutes**](https://joetechnologist.com/2018/02/14/how-to-launch-an-ico-token-on-ethereum-in-90-minutes/)
by Joseph Raczynski, February 2018

[**How to do an initial coin offering (ICO) on Ethereum in less than 20 minutes**](https://medium.com/bitfwd/how-to-do-an-ico-on-ethereum-in-less-than-20-minutes-a0062219374) 
by Moritz Neto, March 2018 

[**The 2018 guide to writing (and testing) real world crowdsale contracts**](https://hashnode.com/post/the-2018-guide-to-writing-and-testing-real-world-crowdsale-contracts-cjcs8dfes00apmdwthw03c2jq)
by Sandeep Panda, January 2018


**Mastering Ethereum Book**

[**Tokens**](https://github.com/ethereumbook/ethereumbook/blob/develop/tokens.asciidoc) 
by Andreas M. Antonopoulos, Gavin Wood, 2018




**Official Ethereum Getting Started Guides**

[**Token - Create your own Cryto Currency with Ethereum**](https://www.ethereum.org/token)
_The Coin - 
Minimum Viable Token •
The code •
Understanding the code •
Noticed the comments? •
How to deploy ++ 
Improve your token -
More basic functions •
Centralized Administrator •
Central Mint •
Freezing of assets •
Automatic selling and buying •
Autorefill •
Proof of Work ++
Improved Coin -
Full coin code •
Deploying ++ 
Now what?_



[**Crowdsale - Create your own Crowdsale - Raising funds from friends without a third party**](https://www.ethereum.org/crowdsale)
_Crowdfund your idea -
Tokens and DAOs •
The code •
Code highlights •
How to use •
Raise funds ++
Extending the crowdsale -
What if the crowdsale overshoots its target? •
Unlimited crowdsale_



**Official Ethereum Standards**

[**ERC-20 Token Standard**](http://eips.ethereum.org/EIPS/eip-20), [(Source)](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-20.md)
by Fabian Vogelsteller, Vitalik Buterin, 2015





## Ethereum Standard #721 Token

_ERC721 = Ethereum Request for Comments (ERC) #721 - Non Fungible Tokens (NFTs) / Unique Bits & Bytes (on the Blockchain)_

See the [Awesome CryptoCollectibles (& CryptoAssets) page »](https://github.com/cryptocopycats/awesome-cryptocollectibles)




## More Articles / Books

[**Get Rich Quick "Business Blockchain" Bible - The Secrets of Free Easy Money**](https://github.com/openblockchains/get-rich-quick-bible) - 
FREE (Online Version) - From Zero to Twenty Million in Three Weeks -
500 000+% Return on Investment (ROI) -
Hot Air Token Sales - HODL! HODL! HODL! - 
To the Moon :chart_with_upwards_trend::chart_with_upwards_trend::chart_with_upwards_trend: -
To the Beach --
_Step 1: Sell hot air. How? ++
Step 2: Pump up your tokens. How? ++
Step 3: Revolutionize the World.  How? ++
Fast Exit Case Studies_




## Blockchain White Papers - The Art of the Deal / Steal - Scam Alert! Scam Alert! Scam Alert!

_Welcome greater fools! Thanks for your money and HODLing the bag!_

[**Blockchain Whitepapers**](https://github.com/openblockchains/blockchain-whitepapers)
includes Savedroid ($SVD) - Frankfurt (Germany)

[**Austrian Blockchain Whitepapers**](https://github.com/austriacodes/blockchain-whitepapers) - the art of the steal / deal made in Austria - collection of token white papers on the blockchain
includes Hero / Herocoin ($PLAY) by Byte Heroes;
Lancer ($LNC) by Blocklancer;
Rotharium ($RTH) by Crypto Future
Pantos ($PAN) by Bitpanda
Crowd ($CRWD) by Conda
Cultural Coin ($CC) by Cultural Places / Oroundo Mobile




## Awesome Awesomeness

_A curated list of awesome lists._

- [**Awesome Token Sale**](https://github.com/holographicio/awesome-token-sale) -- a curated list of token sale resources / (initial coin offerings) ICO resources 

<!-- break - ethereum  -->

- [**Awesome Solidity (Contract Scripts/Services)**](https://github.com/bkrem/awesome-solidity) -- a curated list of awesome solidity resources, libraries, tools and more
- [**Awesome Ethereum Virtual Machine (EVM)**](https://github.com/pirapira/awesome-ethereum-virtual-machine) -- a curated list of resources on the Ethereum Virtual Machine (EVM) - the virtual machine executed on the ethereum network



## Meta

**License**

![](https://publicdomainworks.github.io/buttons/zero88x31.png)

The awesome list is dedicated to the public domain. Use it as you please with no restrictions whatsoever.
