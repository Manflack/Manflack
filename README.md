- 👋 Hi, I’m @Manflack
- 👀 I’m interested in tech and crypto stuffs.
- 🌱 I’m currently learning Solidity and Economy's of NFT games
- 💞️ I’m looking to collaborate on crypto projects.
- 📫 You can contact me by email: marianofauez@live.com

First contribute, NFT game concept economy

![concept economy](concept_1_1.png?raw=true "Concept Economy")
Access to full view and updated [here](https://excalidraw.com/#json=RsOqq9yYxmLizCQTIqVWr,rln-e64V0laR2FmdosbrlQ)

### Bank system, works with follow rules:

- P1: When Game TOKEN falls more than 5%,
the withdraw costs will cost increment by percentage, this feature
promote not withdrawfrom liquidity pool at the same time.

- P2: When Game TOKEN rises more than 5%, if staking enable, increases
rewards and reduce the withdraw cost.


### Considerations:
 - The timelapses on rises/falls to compute the percentaje need to be minor than 1 week.
 - Token[] represents all the tokens that game manage
 - Avoid market prices, ex. bitcoin fall 30%, then the majority of token prices fall, then this will not affect to withdraw costs.
 - The minimum withdraw cost will be 1%.
