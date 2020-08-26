# Interaction Sequences

## Startup Sequence

start-game-->strike-checker-->calculate-score-->
proclaim-winner-->end-game 

## Movement Initiation

As players initially start the game, the ball activates from
left to right, when ball coincides with the player's wall,
the game checks -
if ball hits the 1st player's wall, a point adds up
           to 2nd player's scorecard.
else if it has hit 2nd player's wall, a point adds up
           to 1st player scorecard.

if score of one of the player reaches 10, that player is winner.
After declaration of winner, the game asks player whether he/she
wants to quit, if yes the game terminates, else the game starts
again.

## One score

After strike-checker module finds a strike
it calls the calculate-score module to calculate
score of respective player.
