# Guess_-My_-Number

This project was built as part of a JavaScript course ( https://www.udemy.com/course/the-complete-javascript-course/) assignment to practice DOM manipulation.The html,css,.prettierrc files were given and the game logic was implemented by me using javascript.


🎮 Guess My Number!
A fun number guessing game built with HTML, CSS, and JavaScript.
The computer randomly generates a secret number between 1 and 20, and you have to guess it.
With every wrong attempt, your score decreases — so guess wisely!
________________________________________
📌 About the Game
This is a simple project to practice JavaScript DOM manipulation.
The player interacts with the game via input fields and buttons, and the game dynamically updates messages, scores, and styles based on the guesses.
________________________________________
🎮 Game Rules
1.	A random number between 1 and 20 is generated.
2.	Enter your guess and click Check!.
3.	Feedback messages will appear:
o	📈 Too high! → Your guess is higher than the secret number.
o	📉 Too low! → Your guess is lower than the secret number.
o	👋 Correct guess! → You win, and your score is saved as a highscore (if higher than before).
4.	Each wrong guess reduces your score by 1.
5.	When the score reaches 0, you lose the game.
6.	Click Again! to restart with a new secret number and reset scores.
________________________________________
✨ Features Implemented
•	Random number generation with Math.trunc(Math.random() * 20 + 1)
•	Score tracking (starts at 20, decreases on wrong guesses)
•	Highscore tracking (persists during the session)
•	Dynamic UI updates (messages, background color, number box size)
•	Event handling for Check and Again buttons
•	Full game reset functionality
________________________________________
📂 Project Files
•	index.html → Structure of the game
•	style.css → Styling (layout, fonts, buttons, UI)
•	script.js → Game logic (random number, score, events, DOM updates)
•	.prettierrc → Optional configuration for code formatting
________________________________________
🚀 How to Run
1.	Clone or download the repository.
2.	Open index.html in any modern web browser.
3.	Play the game 🎉



