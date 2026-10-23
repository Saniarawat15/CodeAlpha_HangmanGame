# 🎮 CodeAlpha Hangman Game

A classic **Hangman word-guessing game built using Python 3**. This console-based game challenges players to guess a randomly selected word one letter at a time, with a limited number of incorrect guesses allowed.

The project is beginner-friendly and demonstrates fundamental Python concepts such as loops, conditional statements, strings, lists, and random selection.

## 📌 Features

- 🎲 **Random Word Selection:** Selects a word randomly from a predefined list.
- 🔤 **Letter-by-Letter Guessing:** Allows players to guess one letter at a time.
- ❤️ **Limited Attempts:** Provides a fixed number of incorrect guesses.
- 🧩 **Word Progress Display:** Displays correctly guessed letters and underscores for hidden letters.
- 📝 **Used Letter Tracking:** Keeps track of previously guessed letters.
- 🏆 **Win or Lose Detection:** Announces whether the player wins or runs out of attempts.
- 🔄 **Replay Option:** Allows players to start a new game after finishing.
- 🖥️ **Console Interface:** Provides a simple, interactive text-based gaming experience.

## 💻 Technologies Used

- **Programming Language:** Python 3
- **Module:** `random`
- **Interface:** Command-line / Console
- **Dependencies:** No external libraries required.

## ⚙️ How It Works

1. The game selects a random word from a predefined word list.
2. The word is displayed as underscores, with each underscore representing a hidden letter.
3. The player enters one letter as a guess.
4. If the letter is correct, its position is revealed in the word.
5. If the letter is incorrect, the number of remaining attempts decreases.
6. The game tracks previously guessed letters to help avoid repeated guesses.
7. The player wins by guessing all the letters before running out of attempts.
8. After the game ends, the player can choose to play again.

## 🚀 Getting Started

### Prerequisites

Make sure Python 3 is installed on your computer.

Check your Python version:

```bash
python --version
```

Alternatively, use:

```bash
python3 --version
```

### Installation and Execution

**1. Clone the repository**

```bash
git clone <your-repository-url>
```

**2. Navigate to the project directory**

```bash
cd CodeAlpha_HangmanGame
```

**3. Run the game**

If your Python file is named `hangman.py`, execute:

```bash
python hangman.py
```

Alternatively:

```bash
python3 hangman.py
```

*Note: Replace `hangman.py` with the actual name of your Python source file.*

## 🖥️ Example Gameplay

```text
Welcome to Hangman!

Word: _ _ _ _ _
Used letters: None
Remaining attempts: 6

Guess a letter: a
Correct guess!

Word: _ a _ _ _

Guess a letter: z
Incorrect guess!
Remaining attempts: 5

Guess a letter: p
Correct guess!

Word: _ a p _ _

...

Congratulations! You guessed the word correctly!
Do you want to play again? (yes/no):
```

*Note: This is illustrative gameplay. The actual messages and word displayed depend on your program's implementation and randomly selected word.*

## 🧠 Python Concepts Demonstrated

- Variables and data types
- Strings and string manipulation
- Lists and list operations
- Loops (`while`, `for`)
- Conditional statements (`if`, `elif`, `else`)
- Random selection using `random.choice()`
- User input and output
- Basic game logic
- Input validation and tracking repeated guesses

## 🎯 Project Objective

The objective of this project is to develop a simple word-guessing game while strengthening Python programming fundamentals. It demonstrates how random selection, conditional logic, and loops can be combined to create an interactive console-based application.

## 🔮 Future Enhancements

- Add difficulty levels such as Easy, Medium, and Hard.
- Include visual Hangman stages using ASCII art.
- Add hints for difficult words.
- Implement score tracking and a high-score system.
- Expand the word list with different categories.
- Improve input validation for invalid or repeated guesses.

## 👩‍💻 Internship Details

- **Organization:** CodeAlpha
- **Project:** Hangman Game
- **Programming Language:** Python 3
- **Project Type:** Beginner-level Python game

---

⭐ If you enjoyed this project, consider giving the repository a star!

