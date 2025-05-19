# Rock Paper Scissors - JavaScript Console Game

This is a simple, foundational implementation of the classic Rock Paper Scissors game built entirely using vanilla JavaScript. The game is played through the browser console, where a human player competes against the computer for 5 rounds.

This project was built only using the JavaScript concepts covered in the early stages of The Odin Project. No libraries, no advanced features — just pure logic, functions, and conditionals to build working software from scratch. Even the `for` loop used here was learned and implemented ahead of the curriculum, by choice.

## How to Run:
- Clone the repository to your local machine:
    `git clone https://github.com/your-username/rock-paper-scissors-console.git`
- Open the `index.html` file in any modern browser
- Open DevTools (`Ctrl + Shift + I` or `F12`) and go to the **Console Tab**
- The game will start automatically and prompt you to enter `rock`, `paper`, or `scissors`

## How to Play:
- When prompted, type `rock`, `paper`, or `scissors` in the console.
- The computer randomly picks one of the three choices and the round winner along with the game score is displayed.
- The game proceeds for 5 rounds, and the final score is shown at the end.

## Features:
- Randomized computer choice using `Math.random()`
- Human input via `prompt()`
- Case-insensitive input handling
- Score tracking and winner declaration after each round and after the final round

## Sample Output:
Here’s what you will see in the console while playing the game:
```
Let's play 5 rounds of Rock Paper Scissors!

--- Round 1 ---
You chose rock
The computer chose scissors
You win! rock beats scissors
Current Score - Human: 1 Computer: 0

...
--- Game Over! ---
You are the overall winner!
```
## Developer Note:
This is not a polished project. It is not supposed to be.
It was built purely to practice problem-solving and converting logic into code.
No GUI, no styling, no extra features. Just raw execution.

Portfolio projects with UI and scalability will come next.

## License:
MIT License