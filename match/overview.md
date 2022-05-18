# Overview

Matches are escrows with oracles, where [players](../player/overview.md) and [items](../item/overview.md) join with their signing authorities and the outcomes of the match are determined by the oracle. This means for instance that three players could join a match which represents a multiplayer combat, and the oracle could determine that the first of them is destroyed permanently with all items lost, the second of them loses all items to the third player, and the third player walks away.

{% hint style="warning" %}
In future versions, matches and their oracles must specify what level of change can happen on chain for any joiners into the match, ranging from no-loss to anything-goes. It is up to the joiners to determine if the risk is appropriate and the oracle is trustworthy.
{% endhint %}
