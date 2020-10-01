# TTTGAME@@
-16,8 +16,6 @@ We will be making a Tic Tac Toe game using all of these concepts.

* Fork and clone this repository.

* Run `npm install` to install dependencies.

  * `npm start` - start BrowserSync server

  * `npm run lint:css` - lint CSS

  * `npm run lint:js` - lint JS

* Before you even start working with JavaScript, construct the gameboard. The gameboard page should include the 3x3 grid (of divs), and at minimum a reset button. Using `id` and `class` on clickable elements will help you wire this up in JavaScript afterwards.

* The JavaScript portion will be next

  * Select elements and attach functions via event listeners

@@ -26,18 +24,24 @@ We will be making a Tic Tac Toe game using all of these concepts.

## Requirements

* A user should be able to click on different squares to make a move.

* Every click will alternate between marking an `X` and `O`

* Upon marking of an individual cell, use JavaScript to add a class to each cell to display separate colors.

* Upon marking of an individual cell, use JavaScript to add a class to each cell to display the separate players.

* A cell should not be able to be replayed once marked.

* You should not be able to click remaining empty cells after the game is over.

* Add a reset button that will clear the contents of the board.

* Display a message to indicate which turn is about to be played.

* After the necessary moves have been played, stop game and alert the winner if one player ends up winning with three in a row.

* Detect draw conditions (ties/cat's game) 

* Detect winner: Stop game and declare the winner if one player ends up getting three in a row. 

  * Hint: Determine a set of winning combinations. Check those combinations on the board contents after every move.

**Have Fun** - The best way to learn is by playing with code. Let creativity guide you and try some experiments with JS and CSS and see what you can do.

## Bonuses

* Add a simple AI to support one player vs computer mode. Note that randomly selecting a space would count as "simple". Try that and iterate from there.

* Implement your reset button without refreshing the whole page

* Track player's wins over time

* Add a simple AI to support one player vs computer mode. In this case, "simple" just means having the computer pick a random empty square.

* Make your computer seem more human by adding a short time delay between your turn and the computer's turn.

* Style it up! Get creative, or even make a theme!

## Super Duper Bonus
