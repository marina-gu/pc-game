# This is a [game](https://marina-gu.github.io/pc-game/) with a computer 
- _click the link to Play_

![image](https://github.com/marina-gu/pc-game/blob/main/pc_game%20.png)
----
### _You need to enter a number from 1 to 20 and guess what number the computer has guessed._

![gif](https://github.com/marina-gu/pc-game/blob/main/animation.gif)
----
### This game was created using JavaScript

```JavaScript
function play() {
    const userNumber = document.querySelector("#guess").value;
    input.value = ' ';
  
    if (userNumber < 1 || userNumber > 20) {
        Swal.fire({
            icon: 'error',
            title: 'Oops!',
            text: 'Enter a number from 1 to 20!',
        })
    }
```
