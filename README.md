# Guessing-Game-in-Python-3
There are two players in this game. One is the computer and the second is You! When the game starts, the computer will choose a random number from 1 to 100. Now YOU have to guess which number has the computer chosen. If you guess the number correctly in the first try, well you are a CHAMPION. But even if you don't, you are welcome to make as many guesses until you get the right answer! The computer will prompt you if you are close to the answer in the following way:

1. If your guess is within 10 digits of the correct number, the game will tell you you are 'WARM'
2. If your guess is NOT within 10 digits of the correct number, the game will tell you you are 'COLD'
3. In case you are 'WARM', and your next guess is closer than your previous one, the game will tell you you are 'WARMER' but if your next guess is not closer to the number than your previous guess, then it will tell you are 'COLDER'

Example: 

1. Computer generated Random Number: 50
2. First guess: 30; Prompter: COLD
3. Next guess: 60; Prompter: WARM
4. Next guess: 65; Prompter: COLDER 
5. Next guess: 55; Prompter: WARMER'. 
6. Next guess: 50; Prompter: YOU WIN!
