# PicturePokerLuigi_Python
**A simple but cool Python-based poker game featuring Luigi from Super Mario!**
Draw cards, match poker hands, and play against Luigi with Mario-themed cards. The game continues until the player runs out of coins.

## Features

- Custom 30-card deck
- Mario-themed card ranks
- Betting and raising system
- Option to discard and replace cards
- Hand evaluation system
- Game loop that continues until coins reach 0

## How to Run

1. Make sure Python is installed on your computer.
2. Open the 'picture_poker_luigi_game.ipynb' file
3. Go to the 'Run the Gameplay Loop!!!' section and run the code.

## How to Play

- You start the game with 10 coins.
- At the start of each round, 1 coin is placed into the pot.
- A deck of 30 cards is shuffled.
- You and Luigi are each dealt 5 cards.
- You can choose whether to raise the bet.
- You can choose whether to discard and replace cards in your hand.
- After that, your final hand is compared with Luigi's hand.
- If you win, you gain coins based on the pot and your hand strength.
- If Luigi wins, you lose coins based on Luigi's hand strength.
- If there is a tie, you get the pot back.
- The game ends when your coins reach 0.

## Card Ranking

Cards are ranked from highest to lowest:

1. Star
2. Mario
3. Luigi
4. Fire Flower
5. Mushroom
6. Cloud

## Hand Types

The game checks for these hand types:

- Five of a kind
- Four of a kind
- Full house
- Three of a kind
- Two pair
- One pair
- High card

## Example Round

1. The round starts and 1 coin goes into the pot.
2. You are dealt 5 cards.
3. You decide whether to raise the bet.
4. You decide whether to discard any cards.
5. Luigi's hand and your hand are compared.
6. Coins are added or removed depending on the result.
7. A new round begins if you still have coins left.

## Project Structure

- `create_deck()` creates and shuffles the deck
- `deal_hands()` gives 5 cards to the player and Luigi
- `discard()` lets the player replace selected cards
- `raise_bet()` handles betting
- `hand_eval()` scores a hand
- `hand_compare()` decides the winner
- `play_game()` controls the full gameplay loop

## Notes

This project was made as a Python practice game using functions, loops, conditionals, and lists.
