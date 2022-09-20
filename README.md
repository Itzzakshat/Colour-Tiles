# Color Tiles
This game is based on colours and patterns. Given a 5x5 grid made with tiles of 6 different colors, the goal is to try and make this 3x3 grid in its center. Out of the 25 tiles, one will be empty which can be swapped with any of the four adjacent tiles.

## Normal Mode:
- [x] Make a 5x5 grid with 6 distinct colors and 24 tiles (one grid has to be empty to allow the tiles to move)
- [x] Generate a random 3x3 grid for each game
- [x] Implement scoring (based on the number of moves taken) and a timer
- [x] Include a reset button to start a new game

## Hacker Mode:
- [x] Include sounds in the game (for example, victory music after game completion)
- [x] Create difficulty modes (easy mode have a 3x3 inner grid and 5x5 outer grid with 6 different colors, medium mode have a 4x4 inner grid and 6x6 outer grid with 7 different colors and hard mode have a 5x5 inner grid and 7x7 outer grid with 8 different colors)
- [x] Using local storage, store and display the name and score of the player with the highest score
- [x] Use media queries to make the page responsive on mobile

## Hackermode++
- [x] Make the game multiplayer where two people can play with the same initial board and reach the same solution.
- [x] Player who completes with the least number of moves wins the game.
- [x] Display the least number of moves after the game ends. Maintain a separate high score for two player games.
- [x] Implement difficulty modes with varying grid sizes for multiplayer games