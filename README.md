# Codacoin Core [CODA]
==========================
Information here is subject to change, this is the initial concept.
##License
Codacoin is released under the terms of the MIT license. See [COPYING](COPYING) 
for more information or see http://opensource.org/licenses/MIT.
##Algorithm
For the first 6 months, Codacoin utilizes X11 as a proof of work algorithm. Past this point, for long-term network security and stability, Codacoin switches to standard SCRYPT. At this time (block 262,975), proof of stake is also enabled at a 0.1% interest rate. Once year 5 hits, this interest rate is increased to 0.15%.
##Block Time
60 seconds.
##Difficulty
Rapid retargeting, every block.
##Initial Reward
256 coins per block.
##Interest Accumulation
After month 6, proof of stake is enabled at a 0.1% rate. Once year 5 hits, this is increased to 0.15%.
##Subsidy Halving
The coin reward halves every 262,975 blocks (6 months ~). The subsidy will never drop below 1 CODA.

* *Y1 M1-6:* 256 CODA per block. 67,321,600 issued.
* *Y1 M6-12:* 128 CODA per block. 33,660,800 issued.
* *Y2 M1-6:* 64 CODA per block. 16,830,400 issued.
* *Y2 M6-12:* 32 CODA per block. 8,415,200 issued.
* *Y3 M1-6:* 16 CODA per block. 4,207,600 issued.
* *Y3 M6-12:* 8 CODA per block. 2,103,800 issued.
* *Y4 M1-6:* 4 CODA per block. 1,051,900 issued.
* *Y4 M6-12:* 2 CODA per block. 525,950 issued.
* *Y5+:* 1 CODA per block. 262,975 issued per year. (0.19% inflation in year 5).

##Ports
P2P: 12001

RPC: 12002
##Ticker
CODA
##Services
**Web Wallets**

* https://moolah.io

*Web wallets are not insecure if done properly, but are inherently more prone to attack than a desktop or offline wallet. Never keep all your funds in one place, unless it is securely offline, and keep backups!*

**Exchanges**

* https://trade.moolah.io/

*Exchanges should not be used as a wallet. You should only keep funds that you are intending to trade on them.*

**Merchant Processing**

* https://moolah.io/
