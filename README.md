# Word-Guessing-Game

Word guessing game is a game in which a player has to guess a secret word chosen by the computer. The player guesses one character at a time and if the guessed character is present in the secret word, it is revealed in its correct position. If the guessed character is not present in the secret word, a turn is lost. The player has a limited number of turns to guess the word.

## Instructions to run the game

* Open the Github repository where the game code is hosted.

* Click on the green "Code" button and then select "Download ZIP" to download the code as a ZIP file.

* Extract the ZIP file to a folder on your computer.

* Open a command prompt or terminal window and navigate to the folder where you extracted the code.

* Type ```python word.py``` and press Enter to start the game.

* Follow the prompts to play the game.

## Functionality of the code

* Import the ```random module``` to generate random words from the list.

* Ask the player for their name and greet them.

* Create a list of words from which a word will be randomly selected.

* Use the ```random.choice()``` function to randomly select a word from the list.

* Display the length of the word as blank underscores to the player.

* Initialize an empty string to hold the player's guesses and set the number of turns to 12.

* Create a while loop that continues until the number of turns is greater than 0.

* Initialize a variable named "failed" to 0.

* Iterate through each character in the word.

* If the character is already in the player's guesses, print the character.

* If the character is not in the player's guesses, print an underscore and increment the "failed" variable by 1.

* If there were no failed guesses, the player wins and the word is displayed, and the loop breaks.

* Ask the player to guess a character and add the guess to the player's guesses.

* If the guess is not in the word, decrement the number of turns remaining, and print a message indicating the guess was wrong and the number of turns remaining.

* If the number of turns is equal to 0, the player loses the game.
