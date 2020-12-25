# connectFour

Connect Four (also known as Four Up, Plot Four, Find Four, Four in a Row, Drop Four, and Gravitrips in the Soviet Union) is a two-player connection board game, in which the players choose a color and then take turns dropping colored discs into a seven-column, six-row vertically suspended grid. The pieces fall straight down, occupying the lowest available space within the column. The objective of the game is to be the first to form a horizontal, vertical, or diagonal line of four of one's own discs. Connect Four is a solved game. The first player can always win by playing the right moves.


Main goal here is practicing Jquery without using arrays in Javascript. 

Steps to make a game:

1. First we define buttons with table in html file. We link Jquery file directly from [jQury](https://code.jquery.com/jquery-3.5.1.min.js) web site or you can download and link locally. 
2. We change button parameters in css file.
3. We take input player names and define special color to each player. Each time when player changes, color also changes when click event happens. 
4. For finding row and column index number answer is on [Stackoverflow](http://stackoverflow.com/questions/6139407/getting-td-by-index-with-jquery).
5. After every click on button in table we check horizontal or vertical or diagonal consicutive match of same colors. if there is a match we stop the game announce it with grabbing text on the top with jQuery and change it with winner players name.





![Alt text](https://github.com/firdavsxon/connectFour/blob/main/Dec-25-2020%2009-05-53.gif)
