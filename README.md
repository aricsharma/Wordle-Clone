# Wordle-Clone
An implementation of Wordle in Python than can be played in the terminal.


Wordle Game Simulator (Python)
This is a terminal-based Wordle game clone built in Python. Players have six attempts to guess a hidden five-letter word, receiving feedback on each guess based on letter correctness and position.

Features
Command-line gameplay

Accurate feedback for each letter in the guess

Color-coded output using the colorama library

Modular design with separate classes for game logic and letter state

Requirements
Python 3.7 or higher

colorama library for terminal text coloring

To install dependencies:


wordle-game/
├── play_wordle.py           # Main script to run the game
├── wordle.py                # Core game logic
├── letter_state.py          # Represents state of each letter
├── README.md                # Project documentation


How to Play
Run play_wordle.py.

Enter 5-letter word guesses when prompted.

After each guess, you will see color-coded feedback:

Green: Correct letter in correct position

Yellow: Correct letter in wrong position

White: Letter not in the word

Future Improvements
Random word selection from a dictionary file

GUI version using Pygame

Score tracking and statistics

License
This project is licensed under the MIT License.
