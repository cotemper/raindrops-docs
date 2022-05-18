# Introduction

The Solana ecosystem has a fragmented and very customized way of storing in-game assets on chain, with as many different formats as there are play-2-earn games. However, the methods of storing ordinary NFT data _are_ standardized in the [Metaplex Protocol](https://docs.metaplex.com). The aim of Raindrops Protocol is to do the same thing for game assets.

The Raindrops Protocol is a series of five contracts that govern on-chain or proof-on-chain data specifically for games, allowing any player or item to be interchangeable with any game client that can process them.

Following the [composability](https://en.wikipedia.org/wiki/Composability) doctrine, the Raindrops Protocol lives literally on top of the Metaplex Protocol, further decorating existing NFTs with new metadata about whether they are a [Player](player/overview.md), an [Item](item/overview.md), or both! All contracts within the Protocol are designed to be composed with other Solana contracts enforcing game-specific rules.

The protocol source is available on GitHub:

{% embed url="https://github.com/raindrops-protocol/raindrops" %}

{% hint style="warning" %}
The Raindrops Protocol is in an alpha state and presently only two contracts are eligible for use on Mainnet-Beta (Item and Matches Contract). While we will try to maintain the integrity of PDAs created as contract development iterates, there is no guarantee that this will be possible.
{% endhint %}

## Quick Start

Jump in to the quick start docs and start making your first game's objects with raindrops:

{% content-ref url="quick-start.md" %}
[quick-start.md](quick-start.md)
{% endcontent-ref %}

## Concepts

There are several powerful concepts used across the raindrops protocol. They are outlined under this section

{% content-ref url="concepts/" %}
[concepts](concepts/)
{% endcontent-ref %}

## Guides

Guides are easy-to-follow steps/recipes for how to integrate various common needs you'll have building out a blockchain-backed game

{% content-ref url="guides/overview.md" %}
[overview.md](guides/overview.md)
{% endcontent-ref %}

## Contract References

Explore each contract's reference to get a deep understanding of everything that's possible within the contract

### Item

{% content-ref url="item/overview.md" %}
[overview.md](item/overview.md)
{% endcontent-ref %}

### Match

{% content-ref url="match/overview.md" %}
[overview.md](match/overview.md)
{% endcontent-ref %}

### Player

{% content-ref url="player/overview.md" %}
[overview.md](player/overview.md)
{% endcontent-ref %}

### Namespace

{% content-ref url="namespace/overview.md" %}
[overview.md](namespace/overview.md)
{% endcontent-ref %}

### Staking

{% content-ref url="staking/overview.md" %}
[overview.md](staking/overview.md)
{% endcontent-ref %}
