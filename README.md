# Flashbots Hackathon summary


Grimm Brothers strategy collective include the a subset of the repositories made by Michael Reynolds and Bruno Mazorra during the MEV hackathon.
The main focus of the code is to explain and analyze theoretical strategies and games proposed in the paper (work in progress).


We include the following repositories:

- **Hamelin**:  we explain the strategy and ways of solving it. The strategy and the code are explained (more details in the paper).
- **Fake-bidding-strategy**: Or red-strategy, we present the code and some ideas of the **red** strategy presented in the paper. The strategy is summarized in the paper. Is important to remark that this strategy is no longer useful. However, we think that other builders can make use of it.
- **Price of MEV** we present a simple code to compute the price of MEV of a game played by a given set of address for some blocks.
- **Grim Brothers strategies**: Small report of the strategies.
- **MEV games**: Complete report of MEV games (work in progress).

# Objectives

- Understand and formalize MEV games.
- Quantify mathematically and empirically the Negative externalities of MEV games (Price of MEV).
- Illuminate the Dark Forest.

# Future work

- Compute the Price of MEV using MEV-inspect-py
- Compare efficiencies of different builders in MEV-Boost/PBS world.
- Reveal new zero-sum strategies among searchers and builders.
- Formalize and analyze the trade offs of different builders combinatioral auctions.

# Authors

- [Michael Reynolds](https://twitter.com/0xmireynolds)
- [Bruno Mazorra](https://twitter.com/0xBrMazoRoig)
