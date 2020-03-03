# Guessing-Game-in-Python-3
There are two players in this game. One is the computer and the second is You! When the game starts, the computer will choose a random number from 1 to 100. Now YOU have guess which number has the computer chosen. If you guess the number correctly in the first try, well you are a CHAMPION. But even if you don't, you are welcome to make as many guesses as you until you get the right answer! The computer will prompt you if you are close to the answer. 

1. If your guess is within 10 digits of the correct number, it will tell you you are 'WARM'
2. If your guess is NOT within 10 digits of the correct number, it will tell you you are 'COLD'
3. In case you are 'WARM', and youe next guess is closer than your previous guess, then it will tell you you are 'WARMER' but if your next guess is not closer to the number than you previous guess, then it will tell you are 'COLDER'

Example: 

1. Lets say the computer chose the number 50
2. Our first guess is 30 which is not within the range of 10 digits from 50, so the computer says 'COLD'
3. Our next guess is 60, which is withing 10 digits from 50, so the computer says 'WARM'. Now we know, we are 10 digits away from the correct guess.
4. The next guess is 65, which is farther away from 50 than 60 is. So the computer will say 'COLDER'. 
5. The next guess is 55 which is closer to 50 than 60 is. So the computer will say 'WARMER'. 
6. The next guess is 50 which is the number guessed by the computer. So YOU WIN!
