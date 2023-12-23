Game Hangman
============

![](./img/Hangman.webp)

Can you beat the clock to guess the hidden word before the poor stick figure meets its doom? Hangman is a quick and easy game that’s perfect if you’re trying to kill some time, prove your vocab superiority, or turn a boring old study session into something more exhilarating. 

## About

The game involves one player choosing a word, phrase, or sentence and the other player trying to guess the word by suggesting letters, one at a time. For each incorrect guess, a part of a “hangman” is drawn, such as a head, body, arms, legs and eventually a face. The game ends when the word is guessed correctly or when the hangman is fully drawn.

## Implement Hangman

1. Choose a word or phrase: The first to choose a word or phrase that the player will try to guess. This will be done by creating several lists of words with different levels of difficulty to select randomly a word from one of these lists.
2. Display blanks: Once a word has been chosen, the player who is guessing the word should be shown a series of blanks, each representing a letter in the word. For example, if the word is “apple”, the player should be shown “_ _ _ _ _”.
3. Get input: The player who is guessing the word should be prompted to enter a letter. 
4. Check input: Once the player has entered a letter, the program should check whether the letter is in the chosen word. If the letter is in the word, the program should update the blanks to show the correct letter(s). If the letter is not in the word, the program should draw a part of the hangman and update the number of incorrect guesses.
5. Repeat steps 3 and 4: The program should continue prompting the player to enter a letter and checking the input until the word has been correctly guessed or the hangman is fully drawn.
6. End the game: Once the word has been correctly guessed or the hangman is fully drawn, the game should end and the player should be notified of the outcome.