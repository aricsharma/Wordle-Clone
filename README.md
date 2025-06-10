This is a terminal-based implementation of the classic Wordle game built in Python. Users attempt to guess a hidden five-letter word within six tries, receiving letter-by-letter feedback after each guess. The game includes color-coded output using the colorama library for better visual clarity.

Features
Command-line interface with real-time feedback

Color-coded hints to indicate correct letters and positions

Input validation for word length

Clean, modular code design for easy extensibility

Tech Stack
Language: Python

Terminal Coloring: Colorama

How It Works
The user inputs a five-letter word as a guess.

Each letter is evaluated:

Green for correct letter in the correct position.

Yellow for correct letter in the wrong position.

White for incorrect letters.


License
This project is licensed under the MIT License.
