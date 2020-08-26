# Proclaim winner

## Feature

Checks score of the players
and declares winner accordingly.

## Acceptance Criteria

### Scenario: Score of either of the players reaches 10

  Given: The game is going on.
  
  When: Total score of first or second player reaches 10 .

  Then: proclaim-winner module declares first player as winner,
        if the score of first player is 10 else checks the score of
        second player, if it's 10 then declares second player
        as winner.
