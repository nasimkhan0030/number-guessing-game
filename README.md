# Number Guessing Game
Create a number guessing game where:\
The computer selects a random number between 1 and 100. \
The user has to guess the number by entering their guesses into an input box. \
The app provides feedback such as: \
***"Too high!" \
"Too low!" \
"Congratulations, you guessed it!"*** \
After a correct guess, the user should be able to **restart** the game. 
### HTML Elements: 
An input box for entering the guess. \
A button to submit the guess. \
A display area to show feedback (e.g., too high, too low, or correct). \
A button to restart the game. 
### Logic:
Generate a random number when the game starts. \
Compare the user's guess with the random number. \
Limit the number of guesses (e.g., 10 chances) and show a "Game Over" message if the limit is reached. 
### Example Output 
User enters 50:**"Too low!"** \
User enters 75: **"Too high!"** \
User enters 60: **"Congratulations! You guessed it!"** \
If the user doesn’t guess correctly after **10** tries: **"Game Over! The correct number was (*number*)"** 
