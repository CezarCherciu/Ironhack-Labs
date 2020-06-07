.## Build your own 'Guess the number' game!

# Rules: 
For this example, I have started with a basic 'vanilla version' of the guess the number game => https://www.goobix.com/games/guess-the-number/

After completing the challenge I decided to increase the difficulty a bit by altering the range from 0-100 to 0-1000 and by giving the player 10 chances to guess the computer randomly generated number, instead of 6 chances as in the goobix example. 


# Steps:

1. We first need to import the random package to python. 

2. We define a 'game' function and we assign a randomly generated number to the rand_number variable.

3. Within the same 'game' function we ask the player to input their guess and assign it to the user_guess variable.

4. We compare the user_guess and the rand_number in order to give a hint to the player if the number is to small or too big. For this, we use a while loop, with i < 11, translating into 10 player available guesses.

5. The player looses the game if there are no more remaining guesses but has the option for a rematch after each game. In order to accomplish this, we define another 'main' function in which we assign a new variable (rematch), as well as including the 'game' function. After the game runs within the main function, the player is asked for a y/n input in order to decide for a rematch. 