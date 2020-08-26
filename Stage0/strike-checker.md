# check strikes

## Feature

To check collisions of the ball
and pass to the score module.

## Acceptance Criteria

### Scenario: Ball coincides with the wall

  Given: The game has began.

  When: Ball coincides with the either sides of the wall.

  Then: The module checks if it has hit the either of player's wall,
        if yes it passes the flag to corresponding calculate-score module.
