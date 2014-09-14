A game of Connect 4 in Java
___________________________


  The Connect 4 Game:
  
  The purpose of this assignment is to create a working text-mode version of the popular game, Connect 4. 

  
  Overview of the game:
  
  Connect 4 is a turn based 2 player game played on a 6 rows by 7 columns board. Each player on his turn chooses a column to put a piece at. A piece played in a column falls till it reaches the bottom of the column, or it gets stacked above another piece. The winner is the player who forms a line of 4 adjacent pieces of his color (horizontal, vertical or diagonal). 

  
  Problem statement:
 
  You are required to create a text mode version of the Connect 4 game. The text mode version displays the board using characters (for example „x‟ for one player, „o‟ for the other player, and 
a space for an empty slot). 
  The game starts by asking whether to start a 1 player game (Player vs. Computer), or a 2 player game (Player vs. Player). 

  
  Player vs. Player:
  
  After choosing the type of game, the game starts. When it is a human's turn, the program asks the player for the column to play, and plays the piece for him at this location. 
  If the column is full, or is invalid, the program warns the user about the error, and asks him again to re-enter the column to play. 
  When the game is finished, the program displays the winner.
  If the board is full and no player win, the program displays “Withdraw”

  
  Player vs. Computer:
  
  If the user chooses to play against the computer, the computer should, on his turn, choose a reasonable move, and play it. 
  Notice that you are not required creating a strong computer player. This requirement is totally outside the scope of this assignment. 
  You are also free to choose any method by which the computer chooses its moves. 

  Hints:
  
* You can use two dimensions array.
* Computer can play at any random column. Search how you can generate random number between 1 and 7.
* It will be a plus from you if you can make computer be a little clever . 
