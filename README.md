# wordleBot

Basically this program takes a database of every correct wordle answer and every valid wordle guess to solve wordle. The way it finds the best guess is this:
  1. filter out the possible guesses using the clues from the last guess
  2. use a pre-loaded database of the most frequent letter at each position to rank each remaining possible guess by most likely word.
  3. give the best guess to solve the wordle
  
That's it.
