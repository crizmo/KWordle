# KWordle

Wordle for Kindle e-readers.

## Overview

KWordle is a version of the popular word-guessing game Wordle, specifically designed to work on Kindle e-readers. It features:

- 5-letter word guessing gameplay
- Special indicators for letter positions that work well on black & white displays
- Keyboard input support
- Game statistics tracking

## Installation

1. Download this repository
2. Connect your Kindle to your computer
3. Copy the entire `kwordle` folder and `kwordle.sh` to your Kindle
4. Disconnect your Kindle.
5. Open the `KWordle` folder on your Kindle to start the game.

## How to Play

1. The game selects a random 5-letter word
2. You have 6 attempts to guess the word
3. After each guess, you'll see indicators for each letter:
   - ■ (filled square) means the letter is in the correct position
   - □ (empty square) means the letter is in the word but in the wrong position
   - × means the letter is not in the word
4. Use the on-screen keyboard or your Kindle's keyboard to enter guesses
5. Press "Enter" to submit a guess
6. Try to guess the word in as few attempts as possible!

## Technical Details

- Compatible with Kindle's WebKit-based browser
- Uses ES5 JavaScript for maximum compatibility with older Kindle models
- Optimized for Kindle's screen size and black & white display
- Includes polyfills for older browsers
- Stores game statistics in localStorage
