# Terminal Wordle Game in Python

This is a terminal-based implementation of the classic Wordle game built in Python. Players attempt to guess a hidden five-letter word within six tries, receiving color-coded feedback after each guess for better clarity and engagement.

## Features

- Command-line interface with real-time feedback
- Color-coded hints:
  - Green for correct letter in the correct position
  - Yellow for correct letter in the wrong position
  - White for incorrect letters
- Input validation for word length
- Modular and well-structured codebase for easy extension

## Tech Stack

- **Language**: Python
- **Terminal Coloring**: Colorama

## How It Works

1. The user enters a five-letter word as a guess.
2. Each letter is evaluated against the hidden word.
3. Feedback is provided using colors to indicate:
   - Correct letter and position (green)
   - Correct letter, wrong position (yellow)
   - Incorrect letter (white)
4. The game ends when the correct word is guessed or after six unsuccessful attempts.

## Setup Instructions

1. Clone the repository.
2. Ensure Python is installed on your system.
3. Install the required package:
   ```bash
   pip install colorama
