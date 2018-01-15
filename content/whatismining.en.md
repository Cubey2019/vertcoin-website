---
title: "What is mining"
date: 2018-01-12T01:30:50Z
draft: false
---
## What is mining?
When users of our network send each other Vertcoin, their transactions are secured by a process called mining. Miners will compose a so-called block out of the pending transactions, and need to perform a large number of computations called _hashes_ in order to produce the [Proof-of-Work](https://en.bitcoin.it/wiki/Proof_of_work). With this Proof-of-Work, the block is accepted by the network and the transactions in it become confirmed.

Mining is essentially a race. Whoever finds a valid Proof-of-Work and gets the block propagated over more than half of the Vertcoin network first, wins this race and is allowed to reward themselves with the _block reward_. The block reward is how new Vertcoin come in circulation. This block reward started at 50 VTC when Vertcoin was launched, and halves every four years. The current block reward is 25 VTC. 

### Mining in pools

Because mining is a race, it's difficult for an individual miner to acquire enough computational power to win this race solo. Therefore there's a concept called pool-mining. With pool-mining, miners cooperate in finding the correct Proof-of-Work for the block, and share the block reward based on the work contributed. The amount of work contributed is measured in so-called _shares_. Finding the Proof-of-Work for a share is much easier than finding it for a block, and when the cooperating miners find the Proof-of-Work for the block, they distribute the reward based on the number of shares each miner found. 

### What hardware do I need?

If you want to get started mining Vertcoin, all you need is an ordinary desktop computer with a modern graphics card (GPU). Highend, newer graphics cards yield better results than lowend or older ones. 

The mining performance of a graphics card is expressed in mega-hashes per second (MH/s). If you know the make and model of your graphics card, you can look up the expected performance on [this page](https://www.nicehash.com/profitability-calculator). Choose your model card and look under "Hashing power for each algorithm" for *Lyra2REv2* (The mining algorithm used by Vertcoin).

Be aware that mining with outdated hardware could prove inprofitable: running a miner will incurr electricity costs that may be bigger than your rewards in VTC.