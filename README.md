# tik-tac-toe-VS-computer

Description 

This is a Tik Tac Toe game with 2 levels. While you will be playing against the computer both times, the "unbeatable level" uses an AI algorithm that makes it impossible to beat! 


Brief Example
```
let moves = []
    for (let i=0; i < availSpots.length; i++) {
        let move = {}
        move.index = newBoard[availSpots[i]]
        newBoard[availSpots[i]] = player

        if (player == aiPlayer) {
            let result =minimax(newBoard, huPlayer)
            move.score = result.score
        }
        else {
            let result = minimax(newBoard, aiPlayer)
            move.score = result.score
        }

```

This is a snipit of code from the "unbeatable level", specifically the algorithm whih makes it unbeatable. 

How To Play

Click within a box, right after the computer will make its move. Continue until game is over. 

Press the 'Restart' button to play again 

Press the other button to alternate between levels.

List of Technologies Used 

JavaScript
HTML
CSS
