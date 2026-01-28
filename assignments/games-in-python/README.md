
📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build a playable Hangman game in Python to practice string manipulation, loops, conditionals, and user input handling.

## 📝 Tasks

### 🛠️ Task 1: Implement the Hangman Game

#### Description
Create a command-line Hangman game where the player guesses letters to reveal a hidden word before running out of attempts.

#### Requirements
Completed program should:

- Randomly select a word from a predefined list.
- Display the current word progress using underscores for unknown letters (e.g., _ _ a _ _ ).
- Accept single-letter guesses (case-insensitive) and validate input.
- Track and display incorrect guesses and remaining attempts.
- End the game when the word is fully guessed or attempts are exhausted, showing a win/lose message and revealing the word.
- Keep the user prompts clear and friendly.

### 🛠️ Task 2: Optional Extensions (stretch goals)

#### Description
Add one or more enhancements to improve gameplay or code quality.

#### Examples (optional)

- Show simple ASCII-art hangman stages as attempts are lost.
- Load word list from an external file (e.g., `words.txt`).
- Add difficulty levels that change the allowed attempts or word list.
- Support multi-word phrases and show spaces correctly.
- Save high scores or fastest win times to a small local file.

## 📁 Starter files

- Starter code: [starter-code.py](assignments/games-in-python/starter-code.py)

## ▶️ How to run

Run the game with Python 3 from the `assignments/games-in-python` directory:

```bash
python3 starter-code.py
```

## 🧾 Assessment (teacher-facing)

- **Meets requirements:** Game runs, enforces input rules, and follows the behavior listed above.
- **Code quality:** Clear variable names, functions for major behaviours, and concise, readable logic.
- **Extras:** Any implemented optional extensions earn bonus credit.
