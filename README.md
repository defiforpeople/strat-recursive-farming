# Strategy Recursive Farming

This repo contains the Recursive Farming strategy.

The strategy works in Aave V3 on Avalanche network. 

In it, the user can provide and withdraw liquidty through the smart contract. The smart contract uses Chainlink Keepers for automating interaction that makes the recursion. The recursion consist on supply liqudiity and borrow of some tokens (those that are profitbale is because of the WAVAX rewards on the Avalanche network of Aave V3, since you earn more supplying liquidity than what you pay when borrowing). It uses Chainlink Data Feeds too, for deciding if the recursion is needed or is not necessary, based on the profit that can be generated, and the gas price at that moment in the network.
