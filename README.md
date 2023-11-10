# Raffle
WEB3 Assets Raffle Smart Contract

This smart contract implements a decentralized raffle system, allowing users to create and join raffles with different prizes. The admin can create raffles with specified details such as ticket prices, end times, and prize types (Ether, ERC-20 tokens, or ERC-721 NFTs). Users purchase tickets, either individually or in bundles, by sending Ether to the contract. After the raffle concludes, the admin calls the selectwinner function and it randomly selects a winner, who receives the designated prize. The contract supports various features, including multiple ticket bundles, withdrawal of funds and prizes, and retrieval of raffle details. It ensures transparency and fairness in the selection of winners while providing a decentralized platform for hosting and participating in raffles on the Ethereum blockchain.

***The contract could use CHAINLINK VFRF or some other kind of off chain randomness***
# The select winner function can be easily manipulated if the reward is high enough for miners/mev bots
