# Hangman-Game
## Overview
The Hangman Game is a fun and interactive Python-based word-guessing game. Players must guess letters to reveal a hidden word, but they only have a limited number of lives to do so. Each incorrect guess costs a life, and the game ends when either the player successfully guesses the word or runs out of lives.

### Features
1. Random Word Selection
The game uses a pre-defined word list imported from an external file (hangman_words.py). A word is randomly selected at the start of each game to keep it exciting and unpredictable.

2. Visual Feedback
Hangman stages, represented by ASCII art, show the progress of the game. Each incorrect guess progresses the drawing closer to the full hangman image, providing a visual representation of remaining lives.

3. Interactive Gameplay
Players can guess letters one by one. Correct guesses reveal their positions in the word, while incorrect guesses are tracked, and the player loses a life.

4. Feedback for Guesses
Players are informed if a guessed letter is correct or incorrect.
If they repeat a guess, they are reminded that the letter has already been guessed.
Incorrect guesses are tracked, and the player is shown how many lives remain.
5. Win/Lose Conditions
Win: The player wins when all the letters in the word are correctly guessed.
Lose: The player loses if they run out of lives before completing the word. The game then reveals the correct word.

### How to Play
Start the Game

The game begins by displaying a blank placeholder for the hidden word.
Players are given six lives at the start.
Make Guesses

Input one letter at a time to guess the word.
Correct guesses fill in the blanks for the corresponding letters.
Track Progress

Lives decrease for each incorrect guess, with visual updates provided via ASCII art.
A message notifies players of correct or incorrect guesses, along with their remaining lives.
End the Game

The game ends when the word is guessed completely, or the player runs out of lives.
### Experience
Excitement: Randomized words and limited lives create an engaging challenge.
Visual Fun: ASCII art stages add a unique and entertaining touch to the game.
Interactive: Real-time feedback keeps players involved and motivated.
