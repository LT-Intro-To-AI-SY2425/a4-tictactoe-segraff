# Assignment 4 - Writeup

In assignment 4 we created a basic tic tac toe game so that we could learn object oriented programming. Respond to the following questions.

## Reflection Questions

1. What was the most difficult part to tic-tac-toe?

The most difficult part of tic-tac-toe was determining how to check all of the possible combinations of wins after a move. I used chatGPT to find a more efficient way to check through every instance. ChatGPT told me to return any(all(self.board[pos] == player for pos in combo) for combo in winning_combinations) as a more pythonic way to check all of the combinations that only used one line.

2. Explain how you would add a computer player to the game.

I could add a computer player to the game by implementing an AI strategy for the computer player. You could have the computer select a random empty position using AI, or have the computer evaluate all possible moves and choose the best one. I do not know how to do this.

3. If you add a computer player, explain (doesn't have to be super technical) how you might get the computer player to play the best move every time. *Note - I am not grading this for a correct answer, I just want to know your thoughts on how you might accomplish it.

You could input into the AI code all the possible moves and all the possible outcomes of those moves and have the program choose the move that has the highest probability of winning. 