# Blackjack_Game

### Project Overview
Welcome to Blackjack game! This is a text-based implementation of the classic casino card game. In this game, you'll be playing against a computer dealer. Your goal is to beat the dealer's hand without going over 21.

### Tools and Technologies:

- **Programming Language:** Python
- **IDE/Code Editor:** Jupyter Notebook
- **Libraries:**
  - `random` for shuffling the deck.

### Features
- **Simple Interface**: Enjoy a straightforward text-based interface that lets you focus on the game.
- **Standard Rules**: The game follows standard Blackjack rules, including card values and basic actions like hitting and standing.
- **Single Player**: Play against the computer dealer, making decisions to outplay the dealer's hand.
- **Scoring System**: Keep track of your wins, losses, and ties to see how well you're doing.

### How to Play
1. **Launch the Game**: Start the game by running `Blackjack_Game.ipynb`.
2. **Get Dealt Cards**: You'll be dealt two cards face up, while the dealer receives one face up and one face down.
3. **Make Decisions**: Decide whether to hit (receive another card) or stand (keep your current hand) based on the strength of your hand and the dealer's visible card.
4. **Winning Conditions**:
   - If your hand's total value is closer to 21 than the dealer's without exceeding it, you win.
   - If your hand exceeds 21 (busts), you lose.
   - If both you and the dealer have the same total, it's a tie (push).
   - If the dealer busts, and you haven't, you win.
5. **Controls**:
   - **Hit**: Request another card to be dealt.
   - **Stand**: Keep your current hand and end your turn.
