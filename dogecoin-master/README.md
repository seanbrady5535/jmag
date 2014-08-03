# jmagcoin Core [DOGE, Ð]
==========================

![jmagcoin](http://static.tumblr.com/ppdj5y9/Ae9mxmxtp/300coin.png)

[![Build Status](https://travis-ci.org/jmagcoin/jmagcoin.svg?branch=1.7-dev)](https://travis-ci.org/jmagcoin/jmagcoin)

## What is jmagcoin? – Such coin
jmagcoin is a cryptocurrency like Bitcoin, although it does not use SHA256 as its proof of work (POW). Taking development cues from Tenebrix and Litecoin, jmagcoin currently employs a simplified variant of scrypt.

http://jmagcoin.com/

## License – Much license
jmagcoin is released under the terms of the MIT license. See [COPYING](COPYING)
for more information or see http://opensource.org/licenses/MIT.

## Development and contributions – omg developers
Development is ongoing and the development team as well as other volunteers can freely work in their own trees and submit pull requests when features or bug fixes are ready.

## Very Much Frequently Asked Questions

### How much doge can exist? – So many puppies!
Early 2015 (approximately a year and a half after release) there will be approximately 100,000,000,000 coins.
Each subsequent block will grant 10,000 coins to encourage miners to continue to secure the network and make up for lost wallets on hard drives/phones/lost encryption passwords/etc.

### How to get doge? – To the moon!
jmagcoin uses a simplified variant of the scrypt key derivation function as its proof of work with a target time of one minute per block and difficulty readjustment after every block. The block rewards are fixed and halve every 100,000 blocks. Starting with the 600,000th block, a permanent reward of 10,000 jmagcoin per block will be paid. 

Originally, a different payout scheme was envisioned with block rewards being determined by taking the maximum reward as per the block schedule and applying the result of a Mersenne Twister pseudo-random number generator to arrive at a number between 0 and the maximum reward. This was changed, starting with block 145,000, to prevent large pools from gaming the system and mining only high reward blocks. At the same time, the difficulty retargeting was also changed from four hours to once per block (every minute), implementing an algorithm courtesy of the DigiByte Coin development team, to lessen the impact of sudden increases and decreases of network hashing rate.

The current block reward schedule:

1–99,000: 0–1,000,000 jmagcoin 

100,000–144,999: 0–500,000 jmagcoin

145,000–199,999: 250,000 jmagcoin

200,000–299,999: 125,000 jmagcoin

300,000–399,999: 62,500 jmagcoin

400,000–499,999: 31,250 jmagcoin

500,000–599,999: 15,625 jmagcoin

600,000+: 10,000 jmagcoin

The original block reward schedule with one-minute block targets and four-hour difficulty readjustment:

1–99,000: 0–1,000,000 jmagcoin 

100,000–199,999: 0–500,000 jmagcoin

200,000–299,999: 0–250,000 jmagcoin

300,000–399,999: 0–125,000 jmagcoin

400,000–499,999: 0–62,500 jmagcoin

500,000–599,999: 0–31,250 jmagcoin

600,000+: 10,000 jmagcoin

### Wow plz make jmagcoind/jmagcoin-cli/jmagcoin-qt

  The following are developer notes on how to build jmagcoin on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

  - [OSX Build Notes](doc/build-osx.md)
  - [Unix Build Notes](doc/build-unix.md)
  - [Windows Build Notes](doc/build-msw.md)

### Such ports
RPC 22555
P2P 22556

![](http://dogesay.com/wow//////such/coin)
