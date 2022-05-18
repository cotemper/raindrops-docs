# Overview

Each game may wish to silo players and items from other games, and/or ensure that game clients only load gaming data for that specific game, ignoring NFTs from other games. Conversely, they may wish to provide namespaces that can be “exported” into other games’ namespaces, for cross-playability.

The namespace contract provides a method to attach namespaces to players, items, and other artifacts in the five contracts like matches, so that gaming clients can easily filter them. It also provides an on-chain indexer that can be used to optionally index some, or all namespace elements so that gaming clients can quickly load all artifacts in a namespace. Namespaces can additionally be composed into one another, so that sub-namespacing can be used for more accurate and fast indexing.
