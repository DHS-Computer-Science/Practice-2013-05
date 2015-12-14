# Practice 2013 - 05: Tic Tac Toe For the Win

## Background
You are playing a game of tic-tac-toe with your friend and you are about to win!
Given a tic-tac-toe board that is one step away from victory, make the winning
move!

## Description

### Input
The first line will be the number of games that you are playing. Each game board
will come in 3x3 blocks of characters, where x and o are players’ markers, and a
dash (-) represents an open square. Each board will be followed by a single x or
o to represent which player you are. You will have only two of your markers on
the board, and you are guaranteed to be able to win the game in one move.

### Output
For each case, output the line “Case x:” where x is the case number, on a single
line. On the next 3 lines, output the board as it will look after your winning
move. Use x and o to represent players’ markers and a dash (-) to represent
open squares.

## Sample
### Input
```
3
o--
-o-
xx-
x
o-x
--o
x--
x
xx-
o-o
---
o
```

### Output
```
Case 1:
o--
-o-
xxx
Case 2:
o-x
-xo
x--
Case 3:
xx-
ooo
---
```
