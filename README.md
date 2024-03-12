This project employs the Mace4 application to handle the back-end logic of the "Cruce" game simulation. Mace4, a crucial component of the project's toolkit, serves as a specialized tool for processing the intricacies of the game's logic.

Mace4, part of the TPTP (Thousands of Problems for Theorem Provers) library, is adept at generating models that satisfy given sets of conditions in first-order logic.

The project simulates just two parts of the "Cruce" card game. The first part is the card placement section of the game, where the player is allowed to put down a card in relation to the already placed cards. In "Cruce", the first player will play the first card face up, and then, in clockwise order, each player must respond with a card of the same suit. A player who does not have any cards of the same suit must play a trump card. If the player has no trump cards, only then can they play any card of their choice. In order to not complicate things and focus on the logic behind the game, the first 3 players' cards will be already put down. This means that the user will be able to play as the 4th player, placing down the last card, depending on the previous 3 cards.



![](https://github.com/BAndrei123/AIProject-Cruce-Python-Mace4/blob/main/UI_photo.png)
