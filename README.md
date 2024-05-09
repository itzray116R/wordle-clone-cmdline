# Wordle Game

## Description
This is a simple Python script to play the Wordle game. The game randomly selects a word from a text file, and the player has to guess the word within six attempts. After each guess, the script provides feedback on the correctness of the guessed letters.

## Requirements
- Python 3.x
- termcolor library (install using `pip install termcolor`)

## Usage
1. Ensure you have Python 3.x installed on your system.
2. Install the termcolor library using `pip install termcolor`.
3. Create a text file named `words.txt` containing a list of words, each on a separate line.
4. Run the script and follow the instructions to play the game.

## How to Play
1. The script will randomly select a word from the `words.txt` file.
2. You will be prompted to input a 5-letter word guess.
3. After each guess, the script will provide feedback:
   - Correct letters in the correct position are displayed in green.
   - Correct letters in the wrong position are displayed in yellow.
   - Incorrect letters are displayed as they are.
4. You have six attempts to guess the word correctly.
5. If you guess the word correctly within six attempts, you win. Otherwise, the script will reveal the correct word.

## Example
Let's say the randomly selected word is "apple".

Let's play Wordle:
Type a 5 letter word below and press Enter. You have 6 tries to guess the random word.

Input: table
Output: a[b]p[l]e (letters in brackets indicate correct letters in the wrong position)

Input: apple
Output: [a][p][p][l][e] (all letters in the correct position)
Congratulations! You guessed the word in 2 guesses.
