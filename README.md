# Browser Text Game

## Description

Develop a browser game whose aim is to create a space army, able to conquer new planets fighting against other armies.

## Rules
- Players could join the game using Oauth authentication
- A planet and an empty army will be automatically assigned to each player
- Each player could set up his own environment, providing a name to the planet and to the army
- Each player has a fixed amount of points when joining the game, which could be spent to set up an army
- Any element of the army requires an amount of points, the user could immediately spend all the money to set up his first army
- After setting up the army, the user could decide to see which other planet are in the same galaxy (e.g. other players) and to attack them
- The battle phase would have some pre-defined strategies, which would determine how the army would behave during the battle
- An algorithm would decide who wins each battle, based on army compositions and rules defined to the battle
- A report of the battle will be provided
- After each battle, any user could loose a part or even the entire army
- When a user wins a battle, he automatically owns the other player's planet
- When a user loose all of his planets, he automatically loose the game

## Requirements

- Animations are not explicitly needed, just text
- The game could be multiplayer, so any player could join at any time
- Follow TDD methodology
- Use OOP pattern as much as possible
