# Rock Paper Scissors Game, made with JavaScript. Add scoreboard made with Highcharts.

- <a href="https://github.com/SaraSanchezL/rock-paper-scissors-game">Original Repo</a>
- <a href="https://www.highcharts.com/">HighCharts</a>

The exercise consists of developing the game "Rock, Paper and Scissors". In the game both players have to
choose rock, paper or scissors. It only has two possible outcomes: a tie or a win for a
player and a loss for the other player. We will design the game using JavaScript where a player
will play against the computer.

## Description

The program generates a random movement between paper, rock and scissors (the indications to generate the
random motion are later). Later the user plays, the program compares the
moves and decides if the user has won, lost or tied against the computer. Also in turn the
program is counting the number of points of the player and the computer. The game restarts when
do 10 moves.

## Functionalities JavaScript

- Create a minimal layout with the select, the space for the result and the space for the points of each player.
- Generate a random number with the help of Math.random and Math.ceil.
- Generate a random movement and for that you can follow the following instructions:
  - If the random number generated in the previous step is less than 3, the move is stone.
  - If the random number generated is greater than or equal to 6, the move is paper.
  - and if not, the movement generated is scissors.
- Compare the movement that the player has selected with the movement that the computer has generated, and paint the corresponding clues on the screen.
- Update the point counter on each play.
- The game restarts when 10 moves are made.
- The game ends when it reaches 10 moves, add the necessary code to display a
  Restart Game button that restarts the game when this condition is met and disappears
  the play button.
- When we click on the Restart Game button, this button disappears, put all the
  counters to zero and the Play button reappears.

## Bonus

- Add a graphic representation for the scoreboard that is updated according to the plays, with total rounds, ties, cpu points and player points. Made with HighCharts.
- Add styles with CSS.
