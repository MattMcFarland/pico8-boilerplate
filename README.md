## Game Boilerplate

Here's a boilerplate I plan on using for prototyping different games.

It consists of a splash screen which transitions to the title screen, upon which the user is encouraged to press the play button.  Once the button is pressed, the screen transitions to the "gameplay" state, which is nothing but a text greeting asking the user to press a button, which then results in transitioning to the gameover screen, and finally a press of the button returns the user back to the title screen.

This is a simple implementation of a **Finite State Machine**

Splash -> Title -> Game -> GameOver -> *...Title*

## Demo

## Acknowledgements

* print9() custom font library by [qbicfeet](http://www.lexaloffle.com/bbs/?tid=27669)
* fade transitions by [innomin](http://www.lexaloffle.com/bbs/?tid=2467)

##License (MIT)

```
WWWWWW||WWWWWW
 W W W||W W W
      ||
    ( OO )__________
     /  |           \
    /o o|    MIT     \
    \___/||_||__||_|| *
         || ||  || ||
        _||_|| _||_||
       (__|__|(__|__|
```
