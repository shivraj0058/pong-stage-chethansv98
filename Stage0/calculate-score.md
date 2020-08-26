# Calculate Score

## Feature

Calculates score of the each player.

## Acceptance Criteria

### Scenario: Calculate score for player

  Given: The game is going on.
  
  When: strike-checker module calls the calculate-score module.

  Then: Calculate-score module checks if the ball has hit first player's wall,
        if yes then - add point to second player,
        if no then - add point to first player.
