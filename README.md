# etch.io
A live multi-user collaborative etch-a-sketch built on websockets.

## features
- one etch a sketch board shared by everyone currently on the website
- users give input on how to move the cursor
- every time step (say 1 second or less) the server moves the drawing cursor and updates all the clients via websocket
- users can vote to clear the board
- export boards to imgur

## modes
- in majority mode, everyone votes a direction and the drawing pen moves one pixel in the majority direction
- in vector mode, everyone's directions are summed and the cursor moves multiple pixels at a time

## Notes
  - Have to upgrade to latest Node in order to user Object.values on serverside
