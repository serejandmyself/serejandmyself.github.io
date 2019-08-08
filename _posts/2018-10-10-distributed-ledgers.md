---
layout: post
title: Distributed ledgers, what are they?
categories:
- blog
---

# Distributed ledgers, what are they?

Today's cryptocurrencies are trying out more and more thought out schemes and ways to solve the problems (like scalability), that the blockchain industry had come across over the past decade of its development. 

The “new” ways of solving the problems, include: 
- on chain solutions (increasing block size) 
- layered solutions (there are on, and off-chain solutions) (on chain solutions include things like sharding, wether off chain solutions include things like the development of the lighting network) 
- and, distributed ledger technology, other than the blockchain (should be read as “chain of blocks” literally). 

In this article let's briefly explore the latter as a separate topic. 

In order to understand distributed ledgers, other than bitcoin, and those that follow its footsteps closely, one needs to look at ledgers, that use different architectural operability. Ledgers such as: Hashgraph, IOTA, Byteball and others. 

But first, let's look at what a ledger is and what is a distributed hash table (we will need this information later). 

So, basically a ledger (according to wikipedia): “is a book or a computer file for recording and totaling economic transactions measured in terms of a monetary unit of account by account type, with debits and credits in separate columns and a beginning monetary balance and ending monetary balance two account.” So, that's quite simple. A ledger, is a means to upkeep a record of what it is you are counting / writing down, etc. 

All of us have probably heard the comparison of a blockchain to a simple ledger; but an immutable one. One of the reasons it is immutable, is because its distributed. Which simply means, that its not kept in one place, but over many peers simultaniosuly. By those, allowing everyone to perform a simple check on the “correctness” of the information recorded within the ledger itself (please note that we are not discussing the correctness of the “coming in” information at this stage). 

A hash table is simply a certain structure of data, which implements an associative array in order to store and map out some keys and some values. In other words, it is basically a way of storing information. A distributed hash table, is pretty much the same as above, only now, the information is distributed amongst many nodes. As a result, many peers simultaniosuly, have access to an array that is associated with a certain key. With that in mind, let's move forward. 

One word, that is often used to describe cryptocurrencies that are not associated with the blockchain, is - “Blockchain-free” cryptocurrencies (well, that wasn't a surprise was it?). 
Basically, a Blockchain-free cryptocurrency is a cryptocurrency that uses any mechanisms different from the Blockchain ledger (for example, some major cryptocurrencies like bitcoin, litecoin etc.).


According to cryptowiki: “A Blockchain is a distributed database (authors note - going back to our distributed ledger) that maintains information about all transactions in the form of blocks, protected against revision and tampering. Thus, Blockchain-free cryptocurrencies use other mechanisms to perform the same operations and functions as Blockchain in Blockchain-based cryptocurrencies.” 

In other words, it's like sorbet. You may think its an icecream, but it isn't. The latter is creamy, sorbets are icy. But hell, they look the same. 

So lets and have a look at what technologies and cryptocurrencies there are, that do not use “creamy ice cream” in order to cool you down for the next “moonwalk” (no economical advice hinted on by any means). 

First, we have the DAG (Directed acyclic graph), which is a directed graph that has a certain topological order or a sequence of the vertices that allows it to move from the earlier vertice to the latter in a specific order. 

DAG-based cryptocurrencies have each new transaction confirming one or more previous transactions. As a result of this, transactions perform a structure which resembles a directed graph with no directed cycles. 

But, before comparing the DAG crypto, let's also mention the Hashgraph technology. Hashgraph is different by that is uses a certain communication protocol, called “gossip” (no, it does not speculate about the price). This means, that each transaction broadcasted to the network, “talks” about itself to two randomly chosen nodes, which then, pass it on to other nodes, just until enough nodes in the network know what is going on to that transaction (basically, trying to reach consensus).

To cut the long story short, basically, Hash Graphs, DAGs and blockchains, are simply different, in the topological order in which the information is being stored and recorder (ideally in a distributed manner) and later read by peers \ nodes (in order to reach consensus). 

In order to understand the subject thoroughly, I suggest to do a thoughtful research into the matter, this article has a mere entertaining and informational purpose, rather than a scientific one. 

So, what projects out there work with DAG based systems? 

The five biggest projects are: IOTA, Nano, Holo Chain, IOST and Byteball (there are many others, but in order to keep this short, we will only examine those).

IOTA stands out not only by market capitalization and big partnerships (like Bosch and Volkswagen), but also because it uses what is called “the Tangle”, which is based on a DAG. 

A Tangle is basically a DAG. However, the difference between them, is in the number of minimum transactions, that should be approved in the new transaction. Also, the Tangle uses out microtransactions between the IoT gadgetry (Internet of Things). In comparison to a Blockchain (layout), where microtransactions are processed in the same speed as ordinary transactions, IOTA is much faster, because of the Tangle. And, it also helps to keep away extra processing costs. 

IOTA is promised to be more scalable than any other blockchain, faster and innovative (even as far as using Monte Carlo integration). It promises to bring the IoT on the “blockchain” in a new light. It also has smart contracts and secret transactions in build. Its biggest focus is on machine-to-machine automatic transactions (imagine cars without drivers). It has no fees and boasts around 2.77 billion tokens in circulation. 

Nano (or rail blocks as it was once called) is meant for person to person use and concentrates on creating a payment system. It is a DAG, with average “block” confirmation time between 1 - 10 seconds. It is fee free and as of now, has about 133 million tokens in circulation. 

As the Nano website says: “each account has their own blockchain as part of a larger directed acyclic graph. Each individual user provides the computational power for the verification of their own transactions, meaning entire network is not required to update the overall ledger together in massive blocks.”

Holochain is one of “the new kids on the block”. Is a framework for building fully distributed p2p applications that uses agen-centric approach (author's note - this allows for all kinds of consensus mechanisms from permissioned to permissionless), according to a video by Holo. Holo basically pushes the “chain aspect” from the centre to the edges. Distributed hash tables are implemented in the architecture of Holo, basically, allowing for accessible information at all times (a bit like bit-torrent). It has 133 billion tokens in circulation and is still an ERC 20 token.

IOST, slightly older that the previous entry, has 8.4 billion tokens in circulation as of now. According the the information on their website, IOST is building “an ultra high TPS blockchain infrastructure”. It uses an own consensus algorithm: “Proof-of-Believability”, which enables very high transaction speed and node compliance. It uses such factors as: IOST token balance, reputation-based token balance, network contributions and user behaviors.

In its architecture, IOST uses such mechanisms as: Efficient Distributed Sharding, TransEpoch, Atomix, Proof-of-Believability (PoB) and  Microstate Block (MSB) – which all basically allow it for a “an innovative and secure blockchain paradigm designed to provide horizontal scalability”, according to their white paper.

And finally, Byteball, which was the first DAG to have gained some kind of acceptance or rather “fame”, due to the airdrops it made on bitcoin holders. There are about 662k Gbyte in circulation as of now, and an average confirmation time of a minute. It isn't fee free, as it uses fees as a spam protection mechanism just like a “regular” blockchain network does. According to their website, it boasts such features as: anonymity, multi sigs, smart contracts and private messaging. It aims to be simple. Some even label it “the simple IOTA”. 

Well, to summer up a long story: Hashgraphs, DAGs and other “animals” were not hurt during the writing of this article. However I do advise you to make an own research into the matter, as in my personal opinion “other implementations” of distributed ledgers will grow over time. Do look out for code, research based papers and team quality. Most importantly, remember that this is not a financial advice by any means. 

May the code be with you.    
