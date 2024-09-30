# Hangman Game

## Overview
This is a simple word-guessing game implemented in Python. The player tries to guess a randomly selected word within a limited number of attempts by suggesting letters or guessing the whole word.

## How to Run
1. Clone the repository:
    ```bash
    git clone <repository-url>
    ```

2. Navigate to the project directory:
    ```bash
    cd hangman-game
    ```

3. Run the game:
    ```bash
    python hangman.py
    ```

## Features
- Random word selection from a predefined list.
- Track guessed letters and words.
- Visual display of the hangman figure that updates as incorrect guesses are made.
- Option to replay the game after a win or loss.

## Requirements
- Python 3.x
- A `words.py` file that contains a list of words to be used in the game. Example:
    ```python
    word_list = ["python", "hangman", "random", "coding", "programming"]
    ```

## Game Flow
- At the start, the player is prompted to enter their name.
- The game will randomly choose a word, and the player has to guess it by entering one letter at a time or guessing the whole word.
- For every incorrect guess, a part of the hangman figure is drawn. The game continues until the player either guesses the word or runs out of tries.

## License
This project is licensed under the MIT License.
