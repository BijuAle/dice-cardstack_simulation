# Dice-CardStack Simulation

In games that use the element of randomness to the gameplay, often times, regular faced dices are used. However, for the dice to produce an ideal distribution, the time taken is relatively longer than the time period of game itself. One of the ways of mitigating this situation, is the use of card stack, where the card stack stores the card that corresponds to the combination generated by the dice roll.

## Features
- Simulate hyper-dimensional dices. Notation:
  - [x]d[y], x: no. of dices, y: no. of faces.
  - [x]d[y]-[z], z: no. of cards to remove from combination space. 
- Generate statistically favorable dice roll-card combinations (Discrete Uniform Distribution).
- Peek removed, dealt, & impending cards.
- View combinations & frequency graph.
