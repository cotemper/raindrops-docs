# Quick Start

{% hint style="warning" %}
The Raindrops Protocol is in an alpha state and presently only two contracts are eligible for use on Mainnet-Beta (Item and Matches Contract). While we will try to maintain the integrity of PDAs created as contract development iterates, there is no guarantee that this will be possible.
{% endhint %}

## Install the CLI

To install the CLI at your global level and not tinker with the code directly, use:

```bash
npm install -g raindrops-cli
npm install -g ts-node
```

Commands can now be run using the raindrops-cli commands

```bash
items-cli show_item_class -k <keypair> --env devnet -cp example-configs/itemClass.json
```

## Work in Developer Mode

If you want to work with the codebase to make updates and interact with the contracts you can clone the github repo and run yarn watch from the `js` folder or use `ts-node` to execute client scripts directly without transpiling typescript to javascript.

{% tabs %}
{% tab title="ts-node" %}
```bash
npm install -g ts-node
ts-node js/src/cli/item.ts show_item_class -k <keypair> --env devnet -cp js/example-configs/itemClass.json
```
{% endtab %}

{% tab title="yarn watch" %}
```bash
npm install -g yarn
cd js
yarn
yarn watch   # From another terminal (command takes over the current terminal)
node build/cli/item.js show_item_class -k <keypair> --env devnet -cp example-configs/itemClass.json
```
{% endtab %}
{% endtabs %}

## Getting Help!

{% hint style="info" %}
For the time being, as this is partially a Degeniverse product and partially an open source product, you can get help from the developers in the `raindrops-protocol` channel of the DTP discord: [https://discord.gg/5yjMKVbC](https://discord.gg/5yjMKVbC).&#x20;
{% endhint %}
