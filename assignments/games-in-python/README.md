
# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build the classic Hangman word-guessing game using Python. In this assignment, you will practice string manipulation, loops, conditionals, and user input while creating a complete playable terminal game.

## 📝 Tasks

### 🛠️	Create the Core Hangman Game Loop

#### Description
Write a Python program that randomly chooses a secret word from a predefined list and lets the player guess one letter at a time.

#### Requirements
Completed program should:

- Randomly select one word from a list of at least 5 possible words.
- Display the current word progress using underscores for unknown letters (for example: `_ _ _ _ _`).
- Ask the player for a single-letter guess on each turn.
- Reveal correctly guessed letters in all matching positions.


### 🛠️	Track Attempts and End the Game

#### Description
Add game rules for incorrect guesses, then finish the game with clear win or lose messages.

#### Requirements
Completed program should:

- Track the number of incorrect guesses remaining and show it after each turn.
- Reduce remaining guesses only when the player enters a wrong letter.
- End the game with a win message when the full word is guessed.
- End the game with a lose message when attempts reach zero, and display the correct word.
