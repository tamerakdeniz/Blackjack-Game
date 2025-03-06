# 🃏 Blackjack Game

This is a simple Blackjack game implemented in Python. The game allows you to play against the computer, following the basic rules of Blackjack.

## 🎮 How to Play

1. Run the `main.py` file to start the game.
2. You will be prompted to decide if you want to play a game of Blackjack. Type 'y' to start or 'n' to exit.
3. Both you and the computer will be dealt two cards initially.
4. You can choose to get another card by typing 'y' or pass by typing 'n'.
5. The computer will draw cards until its score is at least 17.
6. The game will compare your score with the computer's score and declare the winner.

## 📜 Rules

- The goal is to get as close to 21 as possible without going over.
- Number cards are worth their face value.
- Face cards (Jack, Queen, King) are worth 10 points.
- Aces can be worth 11 or 1 point, depending on which value keeps the score under 21.
- If your initial two cards sum up to 21, you have a Blackjack and win the game unless the computer also has a Blackjack.
- If you go over 21, you lose the game.

## 📝 Example

```
Do you want to play a game of Blackjack? Type 'y' or 'n': y

Your cards: [10, 7], current score: 17
Computer's first card: 8
Type 'y' to get another card, 'n' to pass: n

Your final hand: [10, 7], final score: 17
Computer's final hand: [8, 9], final score: 17
It's a draw!
```

## 📦 Dependencies

- Python 3.x

## ⚙️ Installation

1. Clone the repository or download the source code.
2. Ensure you have Python 3.x installed on your machine.
3. Run the game:
   ```
   python main.py
   ```

Enjoy playing Blackjack!
