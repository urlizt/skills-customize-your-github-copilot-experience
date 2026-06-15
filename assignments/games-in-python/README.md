
# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build a classic Hangman game in Python that uses string handling, loops, conditionals, and user input to create an interactive word-guessing experience.

## 📝 Tasks

### 🛠️ Create the game setup

#### Description
Set up the Hangman game by defining a word list, selecting a secret word at random, and preparing the game state for guesses.

#### Requirements
Completed program should:

- Use a predefined list of words for the game
- Randomly select one word for the current round
- Display the current progress as underscores and correctly guessed letters, e.g. `_ a _ _ m a n`
- Track letters that have already been guessed

### 🛠️ Implement gameplay and win/loss logic

#### Description
Write the main gameplay loop that accepts letter guesses, updates game state, and ends the game with a win or loss message.

#### Requirements
Completed program should:

- Accept single-letter guesses from the player
- Update and display the word progress after each guess
- Track remaining incorrect attempts and prevent duplicate guesses
- End when the word is fully guessed or the player runs out of attempts
- Print a clear win or lose message at the end of the game
