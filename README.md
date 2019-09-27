# Cardboard Machines

A lighthearted racing game set in a strange world.

The September entry for my 2019 Boardgame Prototype Challenge (https://gist.github.com/andreasfrisch/74fc8bc0fe5b34672c1f5d8dae21f3e7)

## What you need
* A printout of the double sided boards in this repository
* 1 6-sided die per player (to indicate current gear)
* 6 6-sided 'stress' dice
* 30 stress tokens
* 3 life tokens per player
* 3 round tokens for counting the rounds
* 10 Ghost miniatures

_Note: Stress is not related to the mental disease of the same name. Instead it represents the pressure applied to both driver and vehicle during a race_

## Setup
Choose a starting player.
Starting from the starting player and going clockwise, each player places a car on consecutive starting spaces, starting from 1, then 2, etc.

Give each player a gear die set to 1.

Give each player 3 life tokens.

Place the three round markers next to the game board.

Place the 6 Stress dice and all stress tokens within reach of all players

## Taking your turn
On their turn players perform the following three actions in order

* Change gear
* Move
* Test for stress

### Changing Gear
Each player has a die indicating which gear they are currently in.
The gear a player is in determines how fast a player may move in their turn.

In the beginning of a player's turn she may increase her gear, or decrease her gear, by any amount.
If a player decreases their gear by any number higher than 1, that player receives 1 Stress.
If a player increases their current gear level by any number higher than 1, that player receives 1 Stress for every step above 1.

### Moving
When a player moves, he may move up to the amount of spaces indicated by his gear die.
A player may choose to move fewer spaces than his dice indicate, but this will incur a penalty of 1 Stress for every 1 space not moved.

Each time a player move a space, he must move to 1 of the spaces in front of him.
This may give the player a choice between 2 or 3 spaces, depending on the current track layout.

A player will keep moving until all movement points are spent this way.

Certain spaces will have special effects as described below:

#### Moving through other cars
Players may move through other players, but cannot end their movement in the same space as another player.
If a player moves through another player, they both receive 1 Stress.
If a player would end on the same space as another player, the moving player would have to move 1 space less instead as per the normal movement rules.

#### Moving off the far edges of the board
If a player would move off the front edge of the board do the following:
Take the furthest back board away, flip it to its other side, and add it to the front of the board -- thus extending the track.
This does not cost movement, and the moving player must continue moving.

If any player was present on the furthest back board as it was removed, those players immediately crashes.

##### Placing a board
When placing a board make sure to align the arrows in the driving direction.

If the board has one or more ghost-symbols, the moving player may place a ghost on any of the empty squares of the new board before continuing his move.
 
#### Moving through ghosts
If a player moves into a space with a ghost, that player immediately receives 1 Stress.

#### Barely dodging terrain
If all the following is true

* when a player moves
* that player has the option of 3 spaces in front of him
* and the space immediately in front of him is terrain
* and he goes on either side of the terrain during the move

Then that player receives 1 Stress.

#### Ending in terrain
If a player ends in terrain, that player immediately crashes.

### Testing for Stress
After moving, a player will test what effect their current stress level had on their driving.

First; If a player did not change gear this turn, and did not incur any stress during her move, she may return 1 Stress to the supply.

Then the player rolls 1 die for each stress token they currently posses.
Each die has 4 different faces; Blank, Swerve Left, Swerve Right, Malfunction

Remove all blank dice: The driver is in control.
Then remove all pairs of 1 Swerve Left and 1 Swerve Right: The driver may be swerving, but the overall direction remains somewhat the same.

Lastly, in any order, evaluate the remaining dice.
For each remaining Swerve die, move on space in that direction.
This is the only way a player can ever move sideways.

For each malfunction, the player will receive 1 Stress and move 1 space forward.

All normal rules for movement applies to these bonus movements, but the player may execute them in any order they choose.

If a player rolls 2 Malfunction at the same time, the player crashes immediately.

A player can at most roll 6 stress dice.
However, If a player has more than 6 stress, all blank dice must be rerolled

## Crashing
When a player crashes, do the following in order

* Replace the player's car with a ghost; If a player crashes due to hitting a wall, the ghost will appear at the last space the player occupied before hitting the wall
* Reduce the player's current gear by 3 to a minimum of 1.
* Reduce the player's Stress to 1
* That player returns 1 life or 1 life token to the box.
* Place the player on any edge of the third board from the back.

If there is anything to choose, the crashed player chooses.
Then continue with the next player.

## End of the game
The game ends when either there is only one player left, in which case she is the winner, or when all round-tokens have been claimed.
If the game ends from round tokens, whomever have the most life and round tokens left is the winner.
In case of a tie, remaining round tokens breaks ties, then least remaining stress.
