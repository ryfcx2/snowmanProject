# Hangman Game
A CLI-based hangman (or snowman in this case) game with difficulty levels, a bonus round, and a points system.
##  Features
- Hint system
- Bonus round system
- Multiple difficulty levels
- Error handling
- Chatbot interface
- extremely fun
## How It Works
The program first lets the player choose their difficulty, which decides the possible words and amount of guesses. Then it randomly picks a word, hides its letters, and makes the player guess the letters, enter the whole word, or use a hint, while keeping track of guesses and points. Correct guesses show letters and add points, but wrong guesses lose points and use up attempts. If the player wins, they earn a bonus round for more points
How does the game pick a word?: The game uses the random library and uses random.choice() to pick a word from a list of words
How does it check a letter guess against the word?: It checks if n is in the choice list; if it is, it enters a for loop that goes through every position in choice and puts the letter in the corresponding position in the guess variable
How does it decide when the player has won or lost?: It checks if the player's guess is equal to the script's choice. If it is, it enters a bonus round.
## Challenges I Ran Into
I had a problem when trying to make the guessed letters appear in the correct position because I had trouble when a letter appeared more than once, but then I thought of the idea of using a for loop and replacing the '-' in the guess with the correct letter based on the index of the for loop.
## What I'd Improve With More Time
- Dictionary API for more words
- Better scoring system
- Not repeating the bonus round code
- More efficient
- ASCII art
Made by Ryan Gupta — https://github.com/ryfcx2. Go check out my main acc also: https://github.com/ryfcx

