Download Link: https://assignmentchef.com/product/solved-project-3-b
<br>
5/5 - (1 vote)

Write a program that allows 2 people to play a simple dice game. The game should alternate between players until one of them has won. The rules are as follows:



Each turn, a player repeatedly rolls two dice:

If no 1s are rolled, the sum of the dice is added to their turn total and the player’s turn continues, unless they choose to hold.

If a player chooses to “hold”, their turn total is added to their score, and it becomes the next player’s turn.

If a single 1 is rolled, the player scores nothing for that round and it becomes the next player’s turn.

If two 1s are rolled, the player’s entire score is lost, and it becomes the next player’s turn.

The first player to score 100 or more points wins. When the game is over, you should print the score for player 1 and player 2, and also print who won.

You should seed the random number generator using the time() function.

( When testing your program, you might find it useful to be able to get the same sequence of “random” values. To do that, you could pass a numeric literal to srand instead of using the time function, e.g. “srand(42)”. Every time you use the same seed, you’ll get the same sequence.

Make sure you only seed the random number generator once in your program.)