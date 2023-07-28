** MASTERMIND **

Have you ever played Mastermind? One player is the codemaker, and creates a secret combination of colored pegs. The other player is the codebreaker, and guesses. The codemaker answers each guess attempt by indicating only the number of well placed colors and the number of correct but misplaced colors.

*** Problem Description ***

The idea of this kata is to code an algorithm capable of doing the codemaker’s job of answering the number of well placed and mis-placed colors. So your function should take in a code and a guess, and should return:
the number of well placed color (correct color and correct position)
the number of correct color incorrect position

Game Specs:

Colors are: purple, pink, red, blue, yellow, green, white, brown
Each code is 4 colors
Each guess is 4 colors
Blanks not allowed
Repeated color not allowed
