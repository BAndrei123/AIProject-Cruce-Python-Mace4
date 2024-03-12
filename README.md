This project employs the Mace4 application to handle the back-end logic of the "Cruce" game simulation. Mace4, a crucial component of the project's toolkit, serves as a specialized tool for processing the intricacies of the game's logic.

Mace4, part of the TPTP (Thousands of Problems for Theorem Provers) library, is adept at generating models that satisfy given sets of conditions in first-order logic.

The project simulates just two parts of the "Cruce" card game. The first part is the card placement section of the game, where the player is allowed to put down a card in relation to the already placed cards. In "Cruce", the first player will play the first card face up, and then, in clockwise order, each player must respond with a card of the same suit. A player who does not have any cards of the same suit must play a trump card. If the player has no trump cards, only then can they play any card of their choice. In order to not complicate things and focus on the logic behind the game, the first 3 players' cards will be already put down. This means that the user will be able to play as the 4th player, placing down the last card, depending on the previous 3 cards.

The second implemented part is the round winning decision-making. In "Cruce", after each player has played a card, the cards will be taken by the holder of the highest trump card (or the only trump card) played, or, if no trump card has been played, the cards will be taken by the player who played the highest card of the required suit (the suit of the first card) or the first card if no card was higher. Cards of other suits will not be higher, regardless of their value. Once the 4 cards are placed down, the application will determine which card is leading, and, together with it, the winner of the round.

Because this project is aimed to show how can Mace4 use first-order logic to determine the output of the game using some rules, the following aspects of the game "Cruce" will be omitted: announcement, bidding, 4 player gameplay, scoring, and match ending.

![](https://github.com/BAndrei123/AIProject-Cruce-Python-Mace4/blob/main/UI_photo.png)
