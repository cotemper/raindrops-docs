# Introduction

The Solana ecosystem has a fragmented and very customized way of storing in-game assets on chain, with as many different formats as there are play-2-earn games. However, the methods of storing ordinary NFT data _are_ standardized in the [Metaplex Protocol](https://docs.metaplex.com). The aim of Raindrops Protocol is to do the same thing for game assets. The Raindrops Protocol is a series of five contracts that govern on-chain or proof-on-chain data specifically for games, allowing any player or item to be interchangeable with any game client that can process them.

Following the [composability](https://en.wikipedia.org/wiki/Composability) doctrine, the Raindrops Protocol lives literally on top of the Metaplex Protocol, further decorating existing NFTs with new metadata about whether they are a [Player](player/overview.md), an [Item](item/overview.md), or both! All contracts within the Protocol are designed to be composed with other Solana contracts enforcing game-specific rules.



The codebase for this protocol is located here:

{% embed url="https://github.com/raindrops-protocol/raindrops" %}
