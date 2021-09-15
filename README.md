
# Tic-Tac-Toe

My first project, created during my time at General Assembly.
Given a week, our task was to create our own version of the classic game, Tic-Tac-Toe.

### Future features marked if implemented:

- [x]  Reset Button
- [x]  Score board
- [x]  Player name input
- [ ]  AI

#### Built with:

 - Javascript
 - Jquery 3.6.0
 - HTML
 - CSS

#### Known Bugs:

 First round (after refresh)...

 ```javascript
 if (winnerMessage == '') {
   $('#next').text('Next player turn - '+ nextPlayer);
 }
 ```
 ...produces a missed <code>nextPlayer</code> count,\
 subsequent rounds on clicking <code>Reset</code> button execute as expected.

This current version - Human vs Human, no AI.\
Updated GIF below shows first round with missed next player count.\
Proper count of <code>nextPlayer</code> matches up on reset to next round.
##

![game demo](/LatestTicTacToe.gif)


## Requirements

- Internet browser - Preferably Chrome.
- A second player?

## Installation

```
$ git clone https://github.com/PaulCalnan/project0.git
$ cd project0-main
$ open or double click index.html
```

[Or play it right now here!.. ](https://paulcalnan.github.io/TicTacToe/)


## Additional resources

Learn to build your own here!..

- [General Assembly Sydney](https://tinyurl.com/5xm6mun5)
