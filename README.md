<h1 align="center">
Mydogecoin Core [MYDOGE]  
</h1>

Mydogecoin is a community-driven cryptocurrency that was inspired by a Dogecoin and Shiba Inu meme. The Mydogecoin Core software allows anyone to operate a node in the Mydogecoin blockchain networks and uses the Scrypt hashing method for Proof of Work. It is adapted from Bitcoin Core and other cryptocurrencies.

For information about the default fees used on the Mydogecoin network, please
refer to the [fee recommendation](doc/fee-recommendation.md).

**Website:** [mydogecoin.fun](https://mydogecoin.fun)

## Usage 💻

To start your journey with Mydogecoin Core, see the [installation guide](INSTALL.md) and the [getting started](doc/getting-started.md) tutorial.

The JSON-RPC API provided by Mydogecoin Core is self-documenting and can be browsed with `mydogecoin-cli help`, while detailed information for each command can be viewed with `mydogecoin-cli help <command>`. Alternatively, see the [Bitcoin Core documentation](https://developer.bitcoin.org/reference/rpc/) - which implement a similar protocol - to get a browsable version.

### Such ports

Mydogecoin Core by default uses port `22777` for peer-to-peer communication that
is needed to synchronize the "mainnet" blockchain and stay informed of new
transactions and blocks. Additionally, a JSONRPC port can be opened, which
defaults to port `22776` for mainnet nodes. It is strongly recommended to not
expose RPC ports to the public internet.

| Function | mainnet | testnet | regtest |
| :------- | ------: | ------: | ------: |
| P2P      |   22777 |   44556 |   18444 |
| RPC      |   22776 |   44555 |   18332 |

## Communities 🚀🍾

You can join the communities on different social media.
To see what's going on, meet people & discuss, find the latest meme, learn
about Mydogecoin, give or ask for help, to share your project.

Here are some places to visit:

* [Discord](https://discord.gg/JQFCTDyw3G)
* [Mydogecoin Twitter](https://x.com/mydogecoin_fun)

## License - Much license ⚖️
Mydogecoin Core is released under the terms of the MIT license. See
[COPYING](COPYING) for more information or see
[opensource.org](https://opensource.org/licenses/MIT)
