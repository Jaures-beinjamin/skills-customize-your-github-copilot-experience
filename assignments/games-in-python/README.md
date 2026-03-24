
# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Create a Python Hangman game to practice loops, conditionals, string handling, and user input. By the end of this assignment, students should build a complete text-based game with clear game flow and outcome messages.

## 📝 Tasks

### 🛠️ Build the Core Hangman Loop

#### Description
Create the main game loop that chooses a hidden word, accepts one-letter guesses, and updates the displayed progress after each guess.

#### Requirements
Completed program should:

- Randomly choose a word from a predefined word list
- Ask the player to enter one letter at a time
- Display current progress using underscores for unknown letters (for example: `_ _ _ _`)
- Reveal matching letters in all correct positions

### 🛠️ Add Win/Lose Conditions and Feedback

#### Description
Add attempt tracking and ending logic so the game finishes correctly when the player wins or runs out of guesses.

#### Requirements
Completed program should:

- Decrease remaining attempts for incorrect guesses
- End the game with a win message when the full word is guessed
- End the game with a lose message when attempts reach zero
- Show the correct word when the player loses
