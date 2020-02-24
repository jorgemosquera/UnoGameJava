# UnoGameJava
A JAVA CLI implementation of the UNO Game

## Game Description

UNO is a card game originally developed by Merle Robbins in 1971 in Reading, Ohio, United States. UNO is Shedding-type card game, where players start with a hand of cards and the object of the game is to be the first player to discard all cards from one’s hand. The game can have from 2 to 10 players.

### Game Objective

The objective of the game is to be the first player to score 500 points, achieved by being the first to play all of one’s cards and scoring points for the cards still held by the other players. This objective is done by playing several rounds.

### Components of the Application

1. Card. Representing the characteristics of a UNO card.
2. Deck of Cards.
3. Draw Pile.
4. Discard Pile.
3. Player.
4. Round.
5. Game.

### Functional Requirements

1. Game
  1. Register players
  2. Select a Dealer
  3. Play rounds until there is a Game Winner.
2. Round
  1. Setup a round
  2. Check first Draw card
  3. Player Plays.
  4. If there is a winner compute points, if not check card and continue to the next player.
