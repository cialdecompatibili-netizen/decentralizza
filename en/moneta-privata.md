---
layout: single
title: "Private coin: the technology explained"
description: "How a private digital currency works: ring signatures, stealth addresses, hidden amounts, network and risks. A guide for investors and enthusiasts."
author_profile: true
ref: moneta-privata
lang: en
locale: en
permalink: /en/projects/private-coin/
tr: tradotto
tr_hash: 1hy7g4f
---

**Status: idea under study.** No live network, no token for sale, no returns promised. This page explains the technology and logic we are thinking about, for anyone who wants to understand it and maybe take part.

## The problem
On most public blockchains, such as Bitcoin, every transaction is visible to everyone: who pays, who receives, how much. Anyone who knows an address can follow its movements. A private coin is built to do the opposite: privacy is the rule, not an option.

## Three core technical ideas
**1. Ring signatures: hiding who pays.** When you spend, your digital signature is mixed with those of other users ("decoys") taken from the blockchain. From outside, you can see that one member of the ring signed, but not which one.

**2. Stealth addresses: hiding who receives.** The recipient has a public address, but for each payment the sender generates a one-time address. Only throwaway addresses appear on the blockchain, and an observer cannot link them together.

**3. Confidential amounts (RingCT): hiding how much.** Amounts are encrypted with cryptographic commitments. The network can check that the transaction is valid, meaning no money is created from nothing, without seeing the figure. *Range proofs* show that the amounts are positive.

## What remains verifiable
A private coin is not a coin without rules. Nodes still check everything needed: valid signatures, no double spending and a consistent money supply. Privacy concerns what an outside observer can infer, not whether the rules are respected.

## Network and mining
- **Nodes**: anyone can run a node and verify the chain.
- **Mining**: the activity that adds blocks. Some algorithms are designed to be minable with an ordinary processor, so they do not favor only specialized hardware.
- **Issuance**: a coin needs a clear creation rule. A small ongoing issuance can pay those who keep the network running after the initial period.
- **Peer-to-peer network**: there are techniques that make it harder to link a transaction to the IP address of the sender.

## Limits we state plainly
- **It is not absolute anonymity.** Usage mistakes, network metadata and statistical analysis can reduce privacy.
- **Exchanges.** Some exchanges have removed or limited privacy-oriented coins.
- **Rules.** In Europe the rules on crypto-assets and anti-money laundering are changing and must be checked before any commercial activity or fundraising.
- **Technical risk.** Changing cryptographic code without an independent audit is dangerous.
- **Market risk.** A new coin may find no users, liquidity or exchanges.

## For investors
We offer no returns and no shares. At this stage we look for people who help evaluate the idea. Before any capital raising we need legal review and clear rules, as for every project of our startup hub.

## For enthusiasts and developers
We need cryptographers, distributed systems developers, security experts, people who can write documentation and people who want to test. For background on the reference technology read: [Monero (XMR): what it is and how it works](https://cialdecompatibili-netizen.github.io/cryptomagazine/blog/enciclopedia/monero-xmr-cose-e-come-funziona/).

[I want to take part]({{ '/en/contact/' | relative_url }}){: .btn .btn--primary}

*This page is for information only: it is not an investment offer or financial or legal advice.*
