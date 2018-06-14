# Introduction

## Blockchain industry

The blockchain industry and the infrastructure of the Internet of Value are being built  rapidly around the globe, and to many the atmosphere is eerily similar to the building of the Internet in the late ‘90s,   with pioneers and dreamers coming together to build a new future. Tomochain can be a leading part        of this phenomenon through seamlessly merging an ecosystem of applications with cryptographic tokens used by millions of mainstream users with a unique blockchain infrastructure architecture allowing for a fast, secure, frictionless payment and trusted store of value.
Distributed systems have been researched in a ”permissioned setting” where the number of participants in the system and their identities are common knowledge. In 2008, Satoshi Nakamoto - ”proposed his celebrated “blockchain protocol” which attempts to achieve consensus in a permissionless setting: anyone can join (or leave) the protocol execution (without getting permission from a centralized or distributed authority), and the protocol instructions do not depend on the identities of the players” [10]. Later on, Ethereum with its Ethereum Virtual Machine (EVM) proposed several significant enhancements compared to Bitcoin, including Smart Contracts. Both Bitcoin and Ethereum have some issues, especially with transaction processing performance. 

## Approach

In order to construct an efficient and secured consensus protocol for Tomochain, we tackle the following main bottlenecks of classic blockchains:
Efficiency: Existing blockchains as employed by major crypto-currencies(e.g., Bitcoin or Ethereum) do not scale well to handle a large transaction volume, e.g. Bitcoin and Ethereum can handle around 10 transactions/second. This small throughput severely hinders a wide-spread adoption of such crypto- currencies.
Confirmation times: The 10 minutes Bitcoin block-time [1] is significantly larger than network latency. Furthermore, a Bitcoin block requires 5 subsequent blocks following it so that it can be confirmed; thus it takes on average one hour for a transaction to be confirmed (with low confidence). While Ethereum uses a smaller block-time, the average confirmation time still remains relatively high, around 13 minutes [6], [9]. These long confirmation times hinder many important applications (especially smart contract applications).
Fork Generation: The problem of fork chain consumes computational energy, time, and creates potential vulnerabilities for different types of attacks.
With the motivation as mentioned above, our persistent and ultimate goal of research is to propose the consensus protocol focusing on the following key strategies:
Double Validation to strengthen security and reduce fork

....