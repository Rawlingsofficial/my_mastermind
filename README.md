# Welcome to My Mastermind
Mastermind is a game composed of 9 pieces of different colors.
A secret code is then composed of 4 distinct pieces.

The player has 10 attempts to find the secret code.
After each input, the game indicates to the player the number of well placed pieces and the number of misplaced pieces.

## Task
What is the problem? And where is the challenge?
-c [CODE]: specifies the secret code. If no code is specified, a random code will be generated.
-t [ATTEMPTS]: specifies the number of attempts; by default, the playerhas 10 attempts.

## Description
How have you solved the problem?
The program is written in C, and it uses several standard libraries, including stdio.h, string.h, time.h, stdlib.h, and unistd.h.
It defines a constant ALL_CODE_SIZE as 4, which represents the size of the hidden code.
get_round_numbers() that generates a random 4-digit code 
get_numbers() that checks if a given string contains only digits
str_convert_int() that converts a string of characters representing digits to an integer array
main() function, which is the entry point of the program.
Inside the main() function, it allocates memory for three integer arrays: hidden_code (to store the hidden code), prediction (to store the player's guesses), and buffering (to temporarily store user input).
hidden_code. If the player has provided the number of attempts as an argument, it sets the number of attempts to that value (up to a maximum of 10).


## Installation
 How to install your project? npm install? make? make re?
In this project i did not use npm and rest of them .

## Usage
 How does it work?
 "./" to start game './my_mastermind'
For example, if the secret code is "1234" and the code breaker guesses "1523", the code maker would provide feedback that there is one correctly placed peg (the "2" in the third position) and one correctly colored peg in the wrong position (the "3" in the first position). The code breaker can then use this feedback to refine their next guess.

The game continues until the code breaker correctly guesses the code or runs out of turns. If the code breaker guesses the code, they win the game. If they run out of turns without guessing the code, they lose the game.
```
./my_project argument1 argument2
```

### The Core Team


<span><i>Made at <a href='https://qwasar.io'>Qwasar SV -- Software Engineering School</a></i></span>
<span><img alt='Qwasar SV -- Software Engineering School's Logo' src='https://storage.googleapis.com/qwasar-public/qwasar-logo_50x50.png' width='20px'></span>
