# End Game

## Feature

Terminates the game.

## Acceptance Criteria

### Scenario: After declaration of result and players want to quit
  
  Given: The game declares winner.
  
  When: Any player clicks on quit button .

  Then: The game asks whether to quit or to continue,
        if player clicks on quit, the game ends
        else if player clicks continue, the game starts again.
